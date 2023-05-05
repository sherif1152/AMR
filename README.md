# autonomous_mobile_robot



## Package Name
- robot_description_pkg
- gazebo_pkg
- navigtion_pkg

### robot_description_pkg
- urdf 
- meshes
- worlds

### gazebo_pkg
- launch 


### navigtion_pkg
- launch   
- maps
- param
- rviz


## Description
using :
- Urdf
- SLAM
- AMCL 
- Navigtion 


## Run robot in gazebo
```
roslaunch gazebo_pkg gazebo.launch 
```

## Creat 2D map
```
roslaunch navigtion_pkg gmapping.launch
```

## Save the map
```
 rosrun map_server map_saver 
```
## Run navigition in Rviz
```
 roslaunch navigtion_pkg gmapping.launch 
```
this launch have ('Amcl' , 'move_base' , 'Map server' , 'rviz')

------------

![My Image](robot.png)

--------------
![My Image](robott.png)

------------------
![My Image]( map.png)


