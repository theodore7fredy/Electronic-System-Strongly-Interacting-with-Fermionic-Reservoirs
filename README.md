# **Electronic System Strongly Interacting with Fermionic Reservoirs**

This repository provides a comprehensive study and implementation of the non-equilibrium dynamics of an electronic system strongly interacting with two fermionic reservoirs. The work showcases how these strong interactions influence the spectral density and density of states as a function of the band-widths of the fermionic reservoir $\omega$. The project leverages the **Julia** programming language and the **HierarchicalEOM.jl** software for modeling and simulation.

## **Project Overview**

The main goal of this project is to simulate and analyze the dynamics of a strongly interacting electronic system coupled to fermionic reservoirs. By utilizing the **Hierarchical Equations of Motion (HEOM)** formalism, we explore the evolution of:
- **Spectral Density** as a function of ω
- **Density of States** as a function of ω

The repository includes:
- Julia code for implementing the calculations
- A notebook demonstrating the results and visualizations
- A TikZ workflow diagram illustrating the methodology
- A beamer presentation

This project provides insights into nonequilibrium quantum dynamics and highlights the role of strong interactions in open quantum systems.

---

## **Features**

- **Simulation Framework**: Implements the HEOM method using Julia to study non-equilibrium dynamics.
- **Visualization**: Detailed plots of spectral density and density of states as functions of ω.
- **Workflow Documentation**: Includes a TikZ diagram that outlines the computational workflow.
- **Reproducibility**: All package versions and dependencies are specified for accurate reproduction of results.

---

## **Getting Started**

Follow these steps to set up and run the project.

### **Prerequisites**
Ensure you have the following installed:
- [Julia](https://julialang.org/downloads/)  (version = 1.11.4)
- The following Julia packages:
  - [HierarchicalEOM.jl](https://github.com/HierarchicalEOM/HierarchicalEOM.jl) (version 2.5.1)
  - `QuantumToolbox` (version 0.30.0)
  - `SciMLOperators` (version 0.3.13)
  - `LinearSolve` (version 3.7.2)
  - `OrdinaryDiffEqCore` (version 1.22.0)

