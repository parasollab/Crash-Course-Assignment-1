# Parsol Lab Crash Course Assignment 1

This assignment will teach you about the core concepts of the Robot Operating System (ROS), the ROS Navigation stack, and basic Manipulation in ROS.
In this assingment, you will learn:

1. The core components of ROS and when to use them.
2. How to create and build a ROS workspace and package.
3. How to create and launch a ROS node.
4. How to create a ROS publisher and subscriber.
5. How to create a ROS service and client.
6. How to launch the turtlebot3 simulation in Gazebo and RViz.
7. How to use RViz to navigate the turtlebot3 around in simulation.
8. How to use MoveIt! to plan for a manipulator to reach a goal position.

## Prerequisites

Launch the ppl-crash-course docker container using the scripts provided in that repository. The container has all the necessary dependencies installed.

## Part 1: ROS Basics

In this part, you will learn about the core components of ROS, how they work, and how to use them through a set of tutorials.

### 1.1: Read and follow along with the the following tutorials:

1. [ROS Concepts Overview](https://docs.ros.org/en/iron/Tutorials/Beginner-CLI-Tools.html)
2. [Building a ROS package](https://docs.ros.org/en/iron/Tutorials/Beginner-Client-Libraries/Colcon-Tutorial.html)
3. [Creating a ROS workspace](https://docs.ros.org/en/iron/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
4. [Creating a ROS package](https://docs.ros.org/en/iron/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
5. [Writing a simple publisher and subscriber](https://docs.ros.org/en/iron/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html)
6. [Writing a simple service and client](https://docs.ros.org/en/iron/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Service-And-Client.html)
7. [Writing an action server and client](https://docs.ros.org/en/iron/Tutorials/Intermediate/Writing-an-Action-Server-Client/Py.html)
8. [Creating launch files](https://docs.ros.org/en/iron/Tutorials/Intermediate/Launch/Creating-Launch-Files.html)

## Part 2: Navigation in ROS

In this part you will learn how to spawn a turtlebot3 robot into simulation and how to navigate it around using the ROS Navigation stack.

> Ignore any commands for installing packages.

### 2.1: Read and follow along with the following tutorials:

> For all tutorials, select `Humble` at the top of the page.

> Additionally, remove sudo from any command that requires it.

1. [Spawning a robot in simulation](https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/#gazebo-simulation)
2. [Simultaneous Localization and Mapping (SLAM)](https://ouster.com/insights/blog/introduction-to-slam-simultaneous-localization-and-mapping)
3. [Run SLAM with the Turtlebot](https://emanual.robotis.com/docs/en/platform/turtlebot3/slam_simulation/)
4. [Navigation with the Turtlebot](https://emanual.robotis.com/docs/en/platform/turtlebot3/nav_simulation/)
<details>
<summary>Navigation Brief</summary>

> Navigation is to move the robot from one location to the specified destination in a given environment. For this purpose, a map that contains geometry information of furniture, objects, and walls of the given environment is required. The robot uses the map to plan the path to the destination and avoid obstacles in the environment. The robot also uses sensors such as encoders, IMU, and distance sensors to estimate its pose and detect obstacles in the environment. The robot uses the map and sensor information to localize itself in the environment and navigate to the destination.

</details>

5. Navigation with the Physical Turtlebot: TODO

## Part 3: Manipulation in ROS

TODO

### 3.1: Read and follow along with the following tutorials:

1. [MoveIt Quickstart in RViz](https://moveit.picknik.ai/main/doc/tutorials/quickstart_in_rviz/quickstart_in_rviz_tutorial.html)

2. [Learn about the MoveIt Motion Planning Python API](https://moveit.picknik.ai/main/doc/examples/motion_planning_python_api/motion_planning_python_api_tutorial.html)

3. Move the physical robot using MoveIt: TODO

4. Collect a series of joint configurations using MoveItPy: TODO
