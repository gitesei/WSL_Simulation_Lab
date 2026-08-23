<a href="https://colab.research.google.com/github/gitesei/WSL_Simulation_Lab/blob/main/md_simulation.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This notebook guides the user through the setup, simulation, visualization, and analysis of a periodic box of TIP4P/2005 water using OpenMM.

The workflow includes energy minimization, NVT and NPT equilibration, hydrogen-bond analysis, calculation of the oxygen–oxygen radial distribution function, and analysis of rotational dynamics.

## Getting started

1. Open the notebook in Google Colab using the badge above.
2. Enable a GPU through `Runtime > Change runtime type`.
3. Run the cells in order.

The notebook contains short explanations and questions intended to support interpretation of the simulation results.

## Downloading results

The final cell creates a ZIP archive containing:

- `NPT_traj.dcd`: NPT trajectory;
- `EM_top.pdb`: energy-minimized topology;
- `analysis_results.csv`: summary of simulation results;
- `figures/`: plots generated during the analyses.

## Authors

[Eric Fagerberg (@eo-fagerberg)](https://github.com/eo-fagerberg)

[Giulio Tesei (@gitesei)](https://github.com/gitesei)

