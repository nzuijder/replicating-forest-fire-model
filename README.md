# Replicating forest fires
Basic model to replicate a self-organised critical forest fires by Drossel & Schwabl (1992). The goal is to demonsrate self-organised critical dynamics in a simple model. The replication used a forest fire simulation by Foramitti (2021) as a starting point.

## Contents
replicatingforestfires/


├── forest_fire_animation.gif # Animation of dynamics in the model

├── replicating_forest_fires.ipynb # Jupyter notebook version with plots

├── requirements.txt # List of dependencies

├── forest_fire_results.csv # Saved results

└── README.md # Project description and instructions

## Installation  
Clone the repository and install the required packages:  

```bash  
git clone https://github.com/rosamuilu/replicatingforestfires.git  
cd replicatingforestfires  
pip install -r requirements.txt 
``` 

## Running the model
You can run the model directly from replicatingforestfires.ipynb. You can control multiple parametres such as chance of lightning, relation of lightning to regrowth, gridsize and amount of time steps.


## Reference
Drossel, B. & Schwabl, F. (1992). Self-Organized Critical Forest-Fire Model. Physical Review Letters, 69(11), 1629–1632.
https://doi.org/10.1103/PhysRevLett.69.1629

Foramitti, J. (2021). Forest fire model example (AgentPy). Retrieved from https://agentpy.readthedocs.io/en/latest/agentpy_forest_fire.html
