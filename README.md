# Bateman's Equation – Radioactive Decay Chain Solver

This repository contains Jupyter notebooks for solving and visualizing **Bateman’s equations** for radioactive decay chains.  

Bateman’s equations describe the time evolution of the number of nuclei in a chain of radioactive decays, where each nuclide decays into the next one in the chain.

The notebooks are intended as a simple, educational implementation for:
- Computing the population of each nuclide as a function of time.
- Visualizing the decay chain dynamics.
- Exploring how different decay constants and initial conditions affect the system.

---

## Repository Contents

- **`Bateman's_Equation.ipynb`**  
  Main notebook implementing Bateman’s equations, solving the decay chain, and plotting the number of nuclei vs time.

- **`3D_plot.ipynb`**  
  Optional visualization notebook (e.g. 3D plots of nuclide population vs time vs species index / decay constant).

- **`TNANP.pdf`**  
  A PDF document (slides) providing background theory and/or context for the project.

---

## Requirements

To run the notebooks you will need:

- Python 3.x  
- Jupyter Notebook or JupyterLab  
- Common scientific Python libraries, for example:
  - `numpy`
  - `matplotlib`
  - (optionally) `scipy` if you use numerical ODE solvers

You can install the basic dependencies with:

```bash
pip install numpy matplotlib scipy
