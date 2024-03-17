# drone_sim

## 1. To run

### 1. Install ROS-Noetics
```
https://wiki.ros.org/noetic/Installation/Ubuntu
```

### 2. Clone git repo
```
cd
git clone https://github.com/josephjoel3099/drone_sim.git
```

### 3. Build repo
```
cd
cd drone_sim
rosdep install --from-paths src --ignore-src
catkin build
```
### 4. Run sim
```
cd
cd drone_sim
. devel/setup.bash
roslaunch aws_robomaker_small_warehouse_world view_small_warehouse.launch
```

### 5. In a new terminal
```
cd
cd drone_sim
. devel/setup.bash
roslaunch hector_quadrotor_gazebo spawn_quadrotor.launch
```

### 6. Teleop
```
Not setup
```


## 2. Packages
```
Need to research
```


## 3. Authors

- [@josephjoel3099](https://www.github.com/josephjoel3099)


## 4. License

[MIT](https://choosealicense.com/licenses/mit/)

