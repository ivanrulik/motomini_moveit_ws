# motomini moveit ws

This is small project to learn and stablish a step by step process to take a yaskawa robot arm and make it controllable using moveit 2

### Setup
- Ubuntu 22.04 LTS
- ROS2 Humble Desktop installed
- moveit 2 installed

### Steps
1. clone this repo:
```bash
git clone https://github.com/ivanrulik/motomini_moveit_ws.git
```
2. move into the project folder
```bash
cd ~/<your-download-location>/motomini_moveit_ws/
```
3. Source ros2
```bash
source /opt/ros/humble/setup.bash
```
4. build workspace
```bash
colcon build
```
5. Source worksapce
```bash
source install/setup.bash
```
6. Launch moveit demo
```bash
ros2 launch motomini_moveit_config demo.launch.py
```