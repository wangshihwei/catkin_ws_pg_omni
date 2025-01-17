# teleop_keyboard_omni3
Generic Keyboard Teleop for 3 Wheeled Omnidirectional robots

- For package details : [ROS Wiki](http://wiki.ros.org/teleop_keyboard_omni3)

- Motion Analysis of 3 wheeled omnidirectional robot (Theory involved in writing the code): [Blog post](https://yainnoware.blogspot.com/2019/03/three-wheeled-holonomic-robot-theory.html)

- Simulated the three-wheeled robot on Gazebo to test the code. Package Link : [omni_3wd](https://github.com/YugAjmera/omni_3wd)

## Installation
1. `cd ~/catkin_ws/src`
2. `git clone https://github.com/YugAjmera/teleop_keyboard_omni3`
3. `cd ~/catkin_ws`
4. `catkin_make`
5. `source ~/catkin_ws/devel/setup.bash`
6. `source ~/.bashrc`

Change the topic names in this [scipt](teleop_keyboard_omni3.py) according to your robot.

## Launch
Run.
```
rosrun teleop_keyboard_omni3 teleop_keyboard_omni3.py 
```

## Usage

```
Reading from the keyboard !
---------------------------
Moving around:
   u    i    o
   j    k    l
   m    ,    .

For Holonomic mode (strafing), hold down the shift key:
---------------------------
   U    I    O
   J    K    L
   M    <    >


anything else : stop

q/z : increase/decrease max speeds by 10%

CTRL-C to quit
```
