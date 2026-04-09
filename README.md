# CAD files of the INRIA Paris Robotics Lab
This is a collection of the files produced for the Robotics Lab of INRIA Paris, mainly used by the [WILLOW](https://www.di.ens.fr/willow/) team.
An overview of the robots is available [HERE](https://inria-paris-robotics-lab.github.io/Robots/)

We also put references files that we use to 3D model parts on unitree robots. These files arecleaned up parts of the robots with references for screw placement since the models given by unitree are whole body and lack detailling of the screw holes.

# Description of the files :
All files are given in [freecad](https://www.freecad.org/) format (FCStd) or in mesh format (STL)
>[!TIP]  
> Github has a built in stl viewer : click on "[PREVIEW]" for a 3D preview of the piece.

## 3D Parts
### Franka
[ball.FCStd](franka/ball.FCStd): ball end effector, mainly used for contact and force control experiments  
 [[PREVIEW]](franka/ball.stl)
<div align="center">
    <img src=".pictures/franka/ball.png" alt="Franka ball end effector" width="300">
</div>

### Mantis 
[support_orbec_hub.FCStd](mantis/support_orbbec_sync_hub.FCStd) : support to screw the Orbec hub to a vention profile
<div align="center">
    <img src=".pictures/mantis/support_orbec_hub.png" alt="Switch holder for orbec cameras" width="300">
</div>

### Unitree
#### Go2
[go2_replacement_rail_velcro.FCStd](unitree/go2/go2_replacement_rail_velcro.FCStd) : replacement of the aluminium rail bars used on the Unitree Nvidia Jetson backback with velcro slits  
[[PREVIEW]](unitree/go2/go2_replacement_rail_velcro.stl)
<div align="center">
    <img src=".pictures/unitree/go2/go2_replacement_rail_velcro.png" alt="Replacement rail with velcro slits for go2 jetson backpack" width="300">
</div>

[go2_tether.FCStd](unitree/go2/go2_tether.FCStd) : Link between the builtin leash and a carabiner  
[[PREVIEW]](unitree/go2/go2_tether.stl)
<div align="center">
    <img src=".pictures/unitree/go2/go2_tether.png" alt="Tether for go2 strap" width="300">
</div>

[go2_realsense_mount.FCStd](unitree/go2/go2_realsense_mount.FCStd) : Head mount for a realsense D431 camera  
[[PREVIEW]](unitree/go2/go2_realsense_mount.stl)
<div align="center">
    <img src=".pictures/unitree/go2/go2_realsense_mount.png" alt="Tether for go2 strap" width="300">
</div>

### Vention
[vention_cable_holder.FCStd](vention/vention_cable_holder.FCStd) : clip for holding a roll of cable to a vention profile  
[[PREVIEW]](vention/vention_cable_holder.stl)
<div align="center">
    <img src=".pictures/vention/vention_cable_holder.png" alt="Vention cable holder" width="300">
</div>

---
### References
This is a collection of cleaned up 3D meshes of robots that are used to model 3D objects.
#### Unitree
##### G1
[g1_torso_scale1_1.stl](references/unitree/G1/g1_torso_scale1_1.stl) : torso of the unitree G1  
[[PREVIEW]](references/unitree/G1/g1_torso_scale1_1.stl)

##### Go2
[go2_body_clean.stl](references/unitree/Go2/go2_body_clean.stl): main body with the head of the Go2   
[[PREVIEW]](references/unitree/Go2/go2_body_clean.stl)

[go2_body_scaled_1.001:1.stl](references/unitree/Go2/go2_body_scaled_1.001:1.stl): main body with the head of the Go2, scaled up so that when you do a bolean difference the part has a few millimeters of tolerance.   
[[PREVIEW]](references/unitree/Go2/go2_body_scaled_1.001:1.stl)

[go2_headscrew_placement.FCStd](references/unitree/Go2/go2_headscrew_placement.FCStd): CAD files with the placement of the head screws to be used as a base  
[[PREVIEW]](references/unitree/Go2/go2_headscrew_placement.FCStd)