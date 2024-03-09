# Project ROBOT

This is a "top-level" container for the elements of a robot that I am working on.

It contains components as __git submodules__.

The components are:

1.   firware for the code that runs on a PI PICO on board the robot. Can be found at [git@github.com:robertblackwell/pico-bridge-firmare.git]()
2.   a special ROS2 __cpp__ node that implements a custom serial bridge between ROS2 and the code running on the PICO. Can be found at [git@github.com:robertblackwell/ros2-serial-bridge.git]()
3.   custom messages that the bridge node either subscribes to or publishes. Can be found at [git@github.com:robertblackwell/sample_interfaces.git]()
4.   soon-to-be a python implementation of the ROS2 node described in point 2.