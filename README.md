# LOTUS Robot - ROS 2

## How to run
1. Source ros
2. colcon build in the ros2 workspace directory
3. ros2 launch lotus_nav lotus_control_service.launch.py
4. Open another terminal and source ros
5. ros2 run base_station_receiver bs_nav_receiver.py
6. Open a terminal on base station computer in base_station_receiver/base_station/LFE/
7. python3 map.py
