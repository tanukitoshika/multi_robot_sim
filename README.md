# multi_robot_sim
3D simulation of multi robot (TurtleBot) system on Gazebo

This is for ros-kinetic.


## How to Use

`sudo apt install ros-kinetic-turtlebot*`

`sudo apt install ros-kinetic-joy*`

`roslaunch multi_robot_sim robots_gazebo_rviz.launch`

If you want to change world or map
`roslaunch multi_robot_sim robots_gazebo_rviz.launch world_file:=<PATH_TO_WORLD>/world_name.world map_file:=<PATH_TO_MAP>/map_name.yaml`