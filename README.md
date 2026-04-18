# PV Generator Dynamic Model (MATLAB/Simulink)

## Overview
This project presents a dynamic simulation of a photovoltaic (PV) power generation system using MATLAB and Simulink. The model incorporates environmental inputs such as irradiance and temperature to simulate real-world operating conditions.

The system integrates a boost converter, MPPT algorithm, battery storage, and state-space control to achieve efficient power extraction and stable system performance.

---

## Key Features
- Dynamic PV system modeling using irradiance and temperature inputs  
- Implementation of MPPT algorithms for maximum power extraction  
- Boost converter design with PWM-based control  
- Battery integration for energy storage  
- State-space control using LQR and pole placement techniques  
- Monitoring of system parameters such as voltage, current, and power  

---

## System Architecture
1. Environmental inputs (irradiance and temperature) are fed into the PV array  
2. PV output voltage and current are measured  
3. MPPT algorithm determines optimal duty cycle  
4. PWM generator controls the boost converter  
5. Boost converter regulates output voltage  
6. Battery stores generated energy  
7. State-space controller ensures system stability  

---

## Simulation Setup
To run the simulation:

1. Run either:
   - `statespace_ackerman_setup.m`  
   - `statespaceLQRsetup.m`  

2. Open the Simulink model and run the simulation  

---

## Component Design
The following scripts are used for designing system components:

- `passiveparams_overVin&Iin.m` → Inductor and capacitor sizing based on input conditions  
- `passive_parameters_overduty.m` → Parameter variation with duty cycle  

---

## Tools & Technologies
- MATLAB R2019b  
- Simulink  
- Control Systems Toolbox  

---

## Learning Outcomes
- Understanding of photovoltaic system modeling  
- Practical implementation of MPPT techniques  
- Design and control of boost converters  
- Application of state-space control methods (LQR, pole placement)  
- System-level analysis of renewable energy systems  

---

## Conclusion
This project demonstrates an integrated approach to photovoltaic power system design, combining power electronics, control systems, and optimization techniques. It provides a framework for analyzing and improving the performance of solar energy systems under varying conditions.

