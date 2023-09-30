Source Ros2 : 
source /opt/ros/humble/setup.bash

Source UR :
source ~/workspace/ros_ur_drivers/install/setup.bash

Source DepthAI :
source ~/dai_ws/install/setup.bash

ros2 launch ur_robot_driver ur_control.launch.py ur_type:=ur10 robot_ip:=192.168.0.25 launch_rviz:=true

ros2 launch ur_robot_driver ur10.launch.py robot_ip:=192.168.0.25
