# dofbot_controller
Controller of dofbot in sim and realworld

```
../catkin_ws/src
    /MYROBOT_description
        package.xml
        CMakeLists.txt
        model.config
        /urdf
            MYROBOT.urdf
        /meshes
            mesh1.dae
            mesh2.dae
            ...
        /materials
        /plugins
        /cad
```
## The hierarchy is specially adapted for use as a Gazebo model database by means of the following folders/files:
- /home/user/dotbot_ws/src - this is treated as the location of a Gazebo Model Database.

- model.config - This is a required configuration file for Gazebo to find this model folder

- /urdf/dotbot.urdf - This is your robot description file, also used by Rviz, MoveIt!, etc

- /meshes - put your .stl or .dae files in here, just as you would with regular URDFs.