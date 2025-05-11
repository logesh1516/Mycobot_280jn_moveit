# Mycobot_280jn_gazebo
This is a moveit2 simulation of the mycobot 280jn with gripper and camera in ros2 (humble)

# DESCRIPTION
This is a  moveit simulation of my mycobot configuration for pick and place.

# INSTALLATION
```
mkdir -p mycobot_ws/src
cd mycobot_ws/src
git clone https://github.com/logesh1516/Mycobot_280jn_moveit.git
cd ..
colcon build 
```
# MOVEIT DEMO

![Screenshot from 2025-05-11 22-44-44](https://github.com/user-attachments/assets/0abf21e4-c0b7-4fd7-9b56-8f513cdef866)


# SIMULATION
```
cd mycobot_ws
source install/setup.bash
ros2 launch mycobot_moveit_config demo.launch.py
```
