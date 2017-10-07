# CarND-Extended-Kalman-Filter-Project

This Project is the second term of Udacity Self-driving nano-degree project, the goal is to apply Extended Kalman Filter to fuse data from LIDAR and Radar sensors of a self driving car using C++. 

The project is created in the CarND * Extended-Kalman-Filter-Project * folder.

## Run the code
check the * Extended-Kalman-Filter-Project * folder with readme.md with detailed instruction to implement the code.

## Content in Repository
- scr directory with the project code:
  - main.cpp - calls for FusionEKF and kalman_filter file with feed data
  - FusionEKF.cpp - initializes the filter variable, call the predict and update function based on 
  - kalman_filter.cpp- defines predict function , lidar and Radar updates function
  - tools.cpp - calculates the Jacobian matrix and RSME error
  
## Test Result
Based on the dataset 1 result, the error graph is shown below:

![result.png](http://CarND-Extended-Kalman-Filter-Project/CarND-Extended-Kalman-Filter-Project/result.png "Dataset 1 result")

