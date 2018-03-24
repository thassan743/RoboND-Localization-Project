# RoboND-Localization-Project

### catkin_ws is the name of the active ROS Workspace, if your workspace name is different, change the commands accordingly

If you do not have an active ROS workspace, you can create one by:
```sh
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
```

Now that you have a workspace, clone or download this repo into the **src** directory of your workspace:
```sh
$ cd ~/catkin_ws/src
$ git clone https://github.com/thassan743/RoboND-Localization-Project.git
```

Build the project:
```sh
$ cd ~/catkin_ws
$ catkin_make
```

Source the terminal
```sh
source ~/catkin_ws/devel/setup.bash
```

To run the `udacity_bot` program, in three separate terminals run:
```sh
roslaunch udacity_bot udacity_world.launch
roslaunch udacity_bot amcl.launch
rosrun udacity_bot navigation_goal
```

To run the `table_bot` program, in three separate terminals run:
```sh
roslaunch udacity_bot table_bot_world.launch
roslaunch udacity_bot table_bot_amcl.launch
rosrun udacity_bot navigation_goal
```
