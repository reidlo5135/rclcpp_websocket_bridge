# ROS2-MQTT Client - For ROS2-MQTT connection (rclcpp)

## Document
  - [Environment](#environment)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Colcon Build](#clone--colcon-build)
    - [Run Test](#run-test)

## Environment
* <img src="https://img.shields.io/badge/cpp-magenta?style=for-the-badge&logo=cplusplus&logoColor=white">
* <img src="https://img.shields.io/badge/cmake-064F8C?style=for-the-badge&logo=cmake&logoColor=white">
* <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white">
* <img src="https://img.shields.io/badge/ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">

## Installation

### Prerequisites
- [ROS2 setup](https://index.ros.org/doc/ros2/Installation/) for install rclc -
  **INSTALL [ROS2 Foxy-Fitzroy](https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html)**

### Clone & Colcon Build
```bash
source /opt/ros/foxy/setup.bash
git clone https://github.com/reidlo5135/rclcpp_ws_client.git
cd rclcpp_ws_client
colcon build --symlink-install
source install/setup.bash
```

### Run Test
```bash
source rclcpp_ws_client/install/setup.bash
ros2 run rclcpp_ws_client ros_ws_bridge
```