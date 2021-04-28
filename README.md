Reciprocal Collision Avoidance with Acceleration-Velocity Obstacles
===================================================================

<https://gamma.cs.unc.edu/AVO/>

We present an approach for collision avoidance for mobile robots that takes into
account acceleration constraints. We discuss both the case of navigating a
single robot among moving obstacles, and the case of multiple robots
reciprocally avoiding collisions with each other while navigating a common
workspace. Inspired by the concept of velocity obstacles, we introduce the
acceleration-velocity obstacle (AVO) to let a robot avoid collisions with moving
obstacles while obeying acceleration constraints. AVO characterizes the set of
new velocities the robot can safely reach and adopt using proportional control
of the acceleration. We extend this concept to reciprocal collision avoidance
for multi-robot settings, by letting each robot take half of the responsibility
of avoiding pairwise collisions. Our formulation guarantees collision-free
navigation even as the robots act independently and simultaneously, without
coordination. Our approach is designed for holonomic robots, but can also be
applied to kinematically constrained non-holonomic robots such as cars. We have
implemented our approach, and we show simulation results in challenging
environments with large numbers of robots and obstacles.

![Build Status](https://github.com/snape/AVO2/workflows/ci/badge.svg?branch=main)
[![Build Status](https://circleci.com/gh/snape/AVO2/tree/main.svg?style=svg)](https://circleci.com/gh/snape/AVO2/?branch=main)

Copyright 2010 University of North Carolina at Chapel Hill

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

&nbsp;&nbsp;<https://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Please send all bug reports to [geom@cs.unc.edu](mailto:geom@cs.unc.edu).

The authors may be contacted via:

Jur van den Berg, Jamie Snape, Stephen J. Guy, and Dinesh Manocha  
Dept. of Computer Science  
201 S. Columbia St.  
Frederick P. Brooks, Jr. Computer Science Bldg.  
Chapel Hill, N.C. 27599-3175  
United States of America
