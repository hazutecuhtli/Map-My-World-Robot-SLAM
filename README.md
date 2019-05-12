
# Project Introduction

Welcome to Project 3! In this project you will create a 2D occupancy grid and 3D octomap from a provided simulated environment. Furthermore, you will then create your own simulated environment to map as well.

![image.png](attachment:image.png)

Before we get started let’s take a moment to understand where we are and why we are doing this.

After much testing and research we found RTAB-Map to be the best solution for SLAM to develop robots that can map environments in 3D. These considerations come from RTAB-Map's speed and memory management, its custom developed tools for information analysis and, most importantly, the quality of the documentation. Being able to leverage RTAB-Map with your own robots will lead to a solid foundation for mapping and localization well beyond this Nanodegree program. For this project we will be using the rtabmap_ros package, which is a ROS wrapper (API) for interacting with rtabmap. Keep this in mind when looking at the relative documentation.

# Project Steps

This project will draw heavily on previous knowledge in the course. As a roboticist, practice is key to understanding how everything works and how to efficiently debug problems when they arise.

The project flow will be as follows:

- You will develop your own package to interface with the rtabmap_ros package.

- You will build upon your localization project to make the necessary changes to interface the robot with RTAB-Map. An example of this is the addition of an RGB-D camera.

- You will ensure that all files are in the appropriate places, all links are properly connected, naming is properly setup and topics are correctly mapped. Furthermore you will need to generate the appropriate launch files to launch the robot and map its surrounding environment.

- When your robot is launched you will teleop around the room to generate a proper map of the environment.

- You then will build your own simulated environment and apply the code you used to map the supplied environment on this environment.

- Finally you will create a report and organize the required files for submission.

We are excited to see you grow with your ROS skills and we can't wait to see what you build!


```python

```
