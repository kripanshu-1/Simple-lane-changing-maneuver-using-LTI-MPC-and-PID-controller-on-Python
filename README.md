# Comparision-of-simple-lane-changing-maneuver-using-LTI-MPC-and-PID-controller-on-Python

# Model Predictive Control (MPC) for Autonomous Lane Changing

This project demonstrates a comparison of simple lane-changing maneuver using PID and Model Predictive Control (MPC) on a straight road at a constant forward speed. 

## Project Overview
The project applies:
- **Mathematical modeling** of a vehicle’s lateral dynamics
- **State-space representation** of the vehicle model
- **Model Predictive Control (MPC)** for lane-changing maneuvers

## Features
- Predicts the vehicle's future trajectory based on a defined horizon
- Uses MPC to compute optimal steering inputs
- Generates and visualizes the lane-changing motion
- Simulates real-time execution with an animation

## Files in this Repository
- `MAIN_MPC_car_lateral.py` - Main script implementing the MPC and visualization
- `support_files_car.py` - Helper functions for vehicle dynamics and control

## Running the Simulation
- Keep both the files in the same folder.
- Run the main file.

## Learning Outcomes
- Understanding state-space modeling of vehicles
- Implementing a PID and MPC controller for trajectory tracking
- Simulating vehicle motion using Python and Matplotlib
