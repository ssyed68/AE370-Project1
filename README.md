# AE370-Project1
A Python-based data analytics project encompassing data preprocessing, clustering, and visualization, presented with Jupyter Notebooks and a detailed LaTeX report

This repository contains the code and technical report for our AE370 Project 1: _A Numerical Simulation and Analysis of UAV Pitch Dynamics Using RK4_. The project focuses on modeling and analyzing the pitch dynamics of an Unmanned Aerial Vehicle (UAV) using a simplified second-order differential equation. A fourth-order Runge-Kutta (RK4) method is employed for numerical integration, and various control strategies are investigated.

## Project Overview

The UAV pitch dynamics simulation project aims to:
- **Model the UAV pitch dynamics:** Develop a mathematical model based on a second-order differential equation that describes the UAV's pitch motion.
- **Implement numerical integration:** Use the fourth-order Runge-Kutta (RK4) method to solve the model with high accuracy.
- **Analyze control strategies:** Compare the transient responses (overshoot, settling time) under different control inputs, including a simple step control input and a Proportional–Derivative (PD) controller.
- **Perform a convergence study:** Verify that the numerical method achieves the expected order of convergence (global error of $\mathcal{O}(\Delta t^4)$).


## Key Features

- **Modular Code Structure:** Clean separation of data processing, analysis, and visualization routines.
- **Comprehensive Visualization:** Use of Matplotlib for static data representation.
- **Reproducible Experiments:** Jupyter Notebook to document experiments and code evolution.
- **Detailed Documentation:** A technical report in LaTeX that describes the project in depth.

## Repository Structure

```plaintext
AE370-Project/
├── docs/            # LaTeX technical report and supporting documentation
├── code/            # Code documents with implementation
├── .gitignore       # Specifies files and directories to be ignored by Git
├── LICENSE          # Licensing information (MIT License)
├── README.md        # This file: Project overview, setup instructions, etc.
