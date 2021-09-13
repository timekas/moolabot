///////////Instructions////////////////

System specifications
- ROS Melodic (Ubuntu 18.04)

1- clone the package under catkin_ws/src

2- Load the package in workspace by commands: 
$ cd ~/catkin_ws
$ catkin_make
$ source devel/setup.bash

- Robot Mapping SLAM
1. roslaunch robot main.launch
# 2. roslaunch myool_urdf gmapping.launch
3. roslaunch moolabot display.launch	
4. roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
# 5. rosrun map_server map_saver -f ~/map
# - Rocker Mechanism Robot Navigation
# 1. roslaunch robot main.launch
# 2. roslaunch my_robot_navigation room_amcl.launch map_file:=$HOME/map.yaml






