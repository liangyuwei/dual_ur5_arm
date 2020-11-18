## dual_ur5_arm

A half-done implementation of an imitation learning approach to dual-arm peg-in-hole task, together with some other tools.

Only dual-arm movements are considered in learning, force is not considered.


### Some useful tools
1. _Time Optimal Path Parameterization_ that converts a path into time-optimal trajectory while considering velocity and acceleration limits.  
(1) [TOTG](https://github.com/tobiaskunz/trajectories): A service implemented in ```raw_totg``` folder, using code from [ROS implementation](https://github.com/ros-planning/moveit/pull/809).  
(2) [TOPP](https://github.com/quangounet/TOPP) and [TOPP-RA](https://github.com/hungpham2511/toppra): Services implemented in ```dual_ur5_control/script/``` folder as ```TOPP_service.py``` and ```TOPPRA_service.py```. 

