
# Very Large Scale Vehicle Routing Problem

Solving Very large scale capacitated Vehicle Routing Problems (VLSVRPs) that have between 560-1200 Customers.
<br>Based on work carried out by [Feiyue, Golden and Wasil](https://www.sciencedirect.com/science/article/pii/S0305054803003150)

![vectorVRP.jpg](attachment:vectorVRP.jpg)

## Objective
Generate a sequence of deliveries for each vehicle in a homogeneous fleet based at a <u>single</u> depot so that all customers are serviced and the total distance traveled by the fleet is minimized.

Each vehicle/customer node has following constraints:
- fixed vehicle capacity
- vehicle route-length restriction
- customer known demand
- vehicle must leave from and return to the depot
- customer is serviced by exactly one visit of single vehicle
- location of nodes exhibit geometric symmetry

##### Secondary Objective
Our aim is to generate high quality <u>initial feasible solutions</u> (IFS) that are robust and scalable for large scale VRPs. Better IFS allow faster convergence for improvement algorithms as lesser perturbations to the solution is required. 

## Algorithms
- Modified Clark & Wright Savings' (C&W) Algorithm
- Variable Neighborhood Record-to-Record Travelling (VRTR) Algorithm
- Improvement Algorithms
    - One-Point Move
    - Two-Point Move
    - Two-Opt Move

![flowsheet.png](attachment:flowsheet.png)

## Setup
<b>Requirements</b>
    - Python 3.7
    - Jupyter Notebooks
    
<b>Instructions</b>
<br>Download VRPsolver.ipynb and open using jupyter notebook. 
<br>Select problem number from given directory and run simply the code! 
