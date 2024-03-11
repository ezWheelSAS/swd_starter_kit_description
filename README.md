# SWD Starter Kit description

This ROS package contains URDF file to use SWD Starter kit with ROS 1.
The URDF contains also contains the collision model and is suitable for Gazebo simulations. The package has been tested with Noetic.

## Dependent Packages
Install dependent ROS packages:
```
sudo apt install ros-noetic-joy ros-noetic-teleop-twist-joy ros-noetic-hector-mapping ros-noetic-navigation ros-noetic-gazebo-ros
```

## Quickstart

Launch the following command in order to run RViz and visualize the SWD Starter kit:
```
roslaunch swd_starter_kit_description display.launch gui:=True
```

Launch the following command in order to run Gazebo with the SWD Starter kit:
```
roslaunch swd_starter_kit_description gazebo.launch
```
