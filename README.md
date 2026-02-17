This repository contains the minimal simulation code used to generate all results reported in the manuscript.

The model implements two competing predictive systems with asymmetric access to motor commands and evaluates agency attribution as the difference in prediction errors. The code reproduces all numerical results and figures in the paper without requiring additional modules or data.

How to run

Run the main Python script in a standard Python 3 environment:

python3 run_simulation.py


The script performs N = 50 independent simulation runs with different random seeds and automatically generates all result files.

Output

All outputs are saved to a directory named agency_results:

CSV files containing mean and standard deviation values for all reported conditions

PNG figures corresponding to Figures 2–4 in the manuscript

Reproducibility

All results are fully deterministic given the random seeds specified in the script.
No external datasets or pretrained models are required.
