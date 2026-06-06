---
title: "UR5 Rehabilitation Robot Admittance Control and Trajectory Tracking Simulation"
excerpt: "A ROS/Gazebo/RViz-based UR5 rehabilitation robot simulation system with trajectory tracking, force feedback, admittance control, and virtual patient interaction modeling."
collection: portfolio
permalink: /portfolio/ur5-rehabilitation-robot/
---

# UR5 Rehabilitation Robot Admittance Control and Trajectory Tracking Simulation

## Overview

This project builds a UR5-based rehabilitation training simulation platform using ROS, Gazebo, and RViz. The system includes forward and inverse kinematics, trajectory tracking, force feedback, admittance control, virtual patient interaction force modeling, and training report generation.

## My Role

I served as the project leader and was responsible for algorithm design, control module implementation, system integration, and performance evaluation.

My main contributions include:

- Implemented trajectory tracking modules for straight-line, circular-arc, and circular trajectories
- Integrated end-effector force/torque feedback
- Implemented a second-order admittance control module
- Built a virtual patient interaction force model
- Evaluated trajectory tracking and admittance correction performance
- Organized system-level testing and result analysis

## Technical Stack

- ROS
- Gazebo
- RViz
- UR5 robotic arm simulation
- Forward and inverse kinematics
- Trajectory tracking
- Force feedback
- Admittance control

## Key Results

- Average tracking error during complete prescription training: approximately 1.98 mm
- Maximum tracking error: approximately 3.54 mm
- Admittance correction under 1.5 N virtual patient force: approximately 4.40 cm

## Key Challenges

### Trajectory tracking under interaction force

The main challenge was to maintain stable trajectory tracking while introducing simulated patient interaction forces. I used force feedback and second-order admittance control to adjust the robot motion under external interaction.

### System integration

The project required integrating kinematics, trajectory generation, force feedback, control logic, simulation, visualization, and report generation. I improved the system through modular implementation and repeated testing.

## Demo

Demo video and source code will be updated selectively.
