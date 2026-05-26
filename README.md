# Pendubot LQR Simulation

## Overview
Full nonlinear simulation of a Pendubot (two-link underactuated 
robotic system actuated only at the first joint) with LQR balance 
controller and energy-based swing-up. Euler-Lagrange equations of 
motion derived analytically, implemented in MATLAB/Simulink. 
Monte Carlo robustness analysis performed with ±15% parameter 
variation. Drive requirements document extracted to feed motor 
selection for FOC implementation.

## Hardware
- Simulation only this summer
- Physical Pendubot hardware planned for semester one at TAMU

## Software
- MATLAB
- Simulink
- Python (analysis and plotting)

## Project Phases
- Phase 1: Euler-Lagrange EOM derivation on paper
- Phase 2: Nonlinear Simulink simulation
- Phase 3: LQR balance controller design and validation
- Phase 4: Monte Carlo robustness analysis (±15% parameter variation)
- Phase 5: Drive requirements document — peak torque, RMS torque, 
  velocity range, current loop bandwidth
- Phase 6: Energy-based swing-up (stretch goal)

## Outputs
- Drive requirements document feeding FOC motor selection
- LQR gain matrix with verified step response
- Monte Carlo robustness plots
- Phase portrait of swing-up and balance

## Status
In progress — May 2026

## Weekly Log
### Week 1 — May 25 2026
- Repository created
- EOM derivation started on paper
