# Pipe-Cleaning-Robot
## Introduction
This project presents a pipe-cleaning robot designed to efficiently navigate and clean horizontal pipelines. The robot integrates various mechanical and electrical components, along with MATLAB simulations and SolidWorks design. This documentation details the design, implementation, and functionalities of the robot system, including clog detection, motor control, and cleaning mechanisms. This design project was completed as a group effort by three members for the Engineering Systems Design (EE3204) module during semester 3.

## System Overview
The robot detects clogs inside pipelines using sensors and employs a rotating brush and water jet to remove debris. The project combines SolidWorks 3D modeling for mechanical design and MATLAB Simulink for simulation and control system verification.

## Functionalities
### Core Features
- Clog Detection: Identifies clogs inside the pipeline using sensor data, allowing the robot to adjust its operation.
- Motor Control: Utilizes DC motors to drive the robot and control the rotating brush for cleaning.
- Water Jet Cleaning: Employs a rotating water jet to remove dirt and debris from the pipe walls.
- Brush Cleaning: A rotating brush further scrubs the interior of the pipe.
- Simulink Simulation: Models the robot's movement and cleaning process, providing an accurate simulation of its performance.

### Advanced Features
- Autonomous Navigation: The robot can traverse the pipeline autonomously, adjusting speed and movement based on real-time sensor feedback.
- Persistent Data Storage: Stores sensor readings and operational data for post-run analysis.
- Environmental Monitoring: Continuously monitors the pipeline's condition and adjusts cleaning mechanisms accordingly.

## Software Architecture
### Mechanical Design (SolidWorks)
The mechanical design is created using SolidWorks, where key components such as the rotating brush, wheels, and water jet are modeled and assembled. The design considers factors like pipeline diameter, debris type, and material durability.

### MATLAB Simulation (Simulink)
The system is modeled in MATLAB Simulink to simulate the robot's behavior in real-time. Key components include:
- DC Motor Model: For both the robot's movement and the brush rotation.
- Clog Detection Model: Simulates sensor input for detecting blockages in the pipeline.
- Motor Control: Adjusts the robot's speed based on the clog detection model.

## Sensor Integration
The robot integrates various sensors to monitor and react to pipeline conditions:

- Clog Detection Sensors: Detect blockages and trigger the cleaning mechanism.
- Environmental Sensors: Monitor conditions such as temperature, pressure, and pipeline integrity.
