# Navigation DEMO

Navigation DEMO-ICRA2020&DJI RoboMaster 

## Getting Started

This is the demo of navigation. 

### Prerequisites

Ubuntu18.04 &
ROS

```
sudo apt-get install ros-melodic-desktop-full
sudo rosdep init
rosdep update
source /opt/ros/melodic/setup.bash
```

### Installing

A step by step series of examples that tell you how to get a development env running

clone from github

```
sudo mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
sudo git clone https://github.com/lwbdegit/Navigation-Demo-of-ICRA2020-XDU-ZERO-TO-HERO.git
```

Install dependencies

```
sudo  apt-get -f install

```

build

```
cd ~/catkin_ws/
catkin_make

```

## Running the Demo

Main packages used:
roborts_base &
roborts_bringup &
roborts_localization &
roborts_planning

The operation method is as follows.

### running the launch file

run base and navigation

```
roslaunch roborts_bringup roborts.launch
roslaunch roborts_bringup base.launch
```

## Video of the demo

https://pan.baidu.com/s/1KJKnnrIgSfwARNMDcOBR7A
7427

## Authors

XDU 无人驾驶Lab

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



