# Modular-cost-effective-Tribometer
Open-source design and development of a modular, cost-effective pin-on-disc tribometer, including mechanical design, structural validation, servo motor control, and experimental methodology using Arduino Mega and Raspberry Pi 5 with a supportive HMI/GUI.

## Project Overview

This project focuses on the design and development of a modular, cost-effective pin-on-disc tribometer intended for academic and research laboratory use.  

The primary motivation is to explore a scalable and open engineering approach to tribometer design, integrating mechanical structure, drive system selection, control electronics, and experimental methodology within practical cost and fabrication constraints.

## Engineering Scope

The work is structured around the following engineering domains:

- Mechanical design of the tribometer structure and test rig
- Structural validation of the frame and load paths using FEA (ANSYS)
- Drive system selection and transmission design (AC servo motor with Timming pullry drive)
- present Sensor integration for friction force measurement
- Embedded control using Arduino Mega
- High-level control, data logging, and GUI planning using Raspberry Pi 5

## Current Project Status

- Mechanical layout and base structure defined
- Structural validation in progress for load-bearing components
- AC servo motor and AASD-15A driver selected and commissioned
- Speed control algorithem implementing using Arduino Mega
- Raspberry Pi planned for higher-level supervision, GUI, and data logging

## Open Engineering Discussions

The following aspects are under active evaluation and open for technical discussion:

- Validation of structural boundary conditions used in FEA  
- Practical integration of the AASD-15A servo motor driver with Arduino Mega for laboratory setups  
- Communication architecture between Arduino Mega and Raspberry Pi  
- GUI design approaches for laboratory instrumentation and experimental control  

## Repository Structure (Work in Progress)

- `/mechanical-design` – CAD models and drawings  
- `/analysis` – Structural validation and simulation notes  
- `/electronics` – Wiring diagrams and control hardware  
- `/firmware` – Arduino control logic and Raspberry Pi (Python) code for GUI  
- `/documentation` – Experimental methodology and design notes  
