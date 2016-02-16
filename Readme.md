This program shows how to use the new Kinect with PCL.
Copyright (C) Steven Hickson 2014. See License.txt

This is preliminary software and/or hardware and APIs are preliminary and subject to change.

This uses CMake to find PCL and OpenCV to compile appropriately so it requires all the dependencies of PCL and OpenCV.

The PCL_Kinect2SDK.cpp file is an example of how to use the grabber.
It now works with the libfreenect2 opensource Kinect2 Driver


NOTE: You cannot bind an image callback and a pointcloud callback at the same time. You can only use image/depth callback or a pointcloud callback. This is due to Mat memory management and will be fixed in the new version.

sources from here https://github.com/giacomodabisias/libfreenect2pclgrabber


Peter Weßeler:
I combined the https://github.com/giacomodabisias/libfreenect2pclgrabber Grabber and  PCL_Kinect2SDK. Now i can run PCL Kinfu Large Scale with Kinect2 under Ubuntu

Dependences:
https://github.com/OpenKinect/libfreenect2/

