# regression_of_the_friction_coefficient
[![State of the Art PUTany dataset](https://img.shields.io/badge/State%20of%20the%20Art-PUTany%20dataset-blue)](https://drive.google.com/file/d/1QP-a1Y78LaKVN_mLt91b_10T_5YDyVD_/view?usp=sharing)
## Overview
The tests of selected machine learning algorithms for the task of regression of friction coefficient based on the tactile data. 

## Contents 
The repository contains the tests of the following models: 

* Stacked Conv1D+GRU+FC model - my own implementation
* Stacked ResidualConv1D+BidirectionalGRU+FC - used by scientists at Poznań University of Technology (IRIM) in the THING project.  
* Number of architectures (so far - untuned) from the [tsai](https://github.com/timeseriesAI/tsai) framework.  

## Summary
The issue of mapping readouts from force/torque sensors onto the value of a friction coefficient can be beneficial for providing feedback to the various control routines. 
Examples of issues where friction coefficient regression may be applicable are a contact of a walking robot leg with the surface or contact of a manipulator end-effector with an object in a frictional motion.
This work focuses on examining a neural network-based solution to the friction coefficient regression problem, both in terms of examining the potential of state-of-the-art architectures and proposing a specific solution, and examining its usefulness for the potential practical applications mentioned above, using regression quality assessment tools. 
