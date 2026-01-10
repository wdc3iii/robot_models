# robot_models
Robot Models for RL

## Unitree G1
These models for the Unitree G1 are modifications of the URDF files available at https://github.com/unitreerobotics/unitree_ros/blob/master/robots/g1_description/README.md. The contact model has been simplified, to include only (unless otherwise specified) is four point contacts on the foot and a sphere at the pelvis.

 - `full`: The full Unitree G1 URDF [g1_29dof_with_hand_rev_1_0](https://github.com/unitreerobotics/unitree_ros/blob/master/robots/g1_description/g1_29dof_with_hand_rev_1_0.urdf).
 - `27dof`: Fingers and extra waist DoFs fixed [g1_29dof_lock_waist_rev_1_0](https://github.com/unitreerobotics/unitree_ros/blob/master/robots/g1_description/g1_29dof_lock_waist_rev_1_0.urdf).
 - `21dof`: Modification of 23dof (wrist and extra waist fixed) with wrist roll fixed [g1_23dof_rev_1_0.urdf](https://github.com/unitreerobotics/unitree_ros/blob/master/robots/g1_description/g1_23dof_rev_1_0.urdf).
 - `21dof_2cyl`: 21dof, but foot contact model is two cylinders.
 - `21dof_9pt`: 21dof, but foot contact model is 9 spheres (same as four spheres, with midlines)
 - `21dof_box`: 21dof, but foot contact model is a box. 
