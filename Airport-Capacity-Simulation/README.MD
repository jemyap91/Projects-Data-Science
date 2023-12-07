# Airport Capacity Simulation Exercise

Welcome to the Airport Capacity Simulation Exercise! In this project, I will simulate a simplified airport security system at a busy airport. The goal is to analyze and optimize the system by varying the number of ID/boarding-pass checkers and personal-check queues to keep average wait times below 15 minutes.

## Assumptions

In this simulation, the following assumptions are made (these can be changed based on the requirments of the simulation)

1. Passengers arrive according to a Poisson distribution with λ1 = 50 per minute (mean interarrival rate λ1 = 0.02 minutes) to the ID/boarding-pass check queue. 
2. Several servers handle this queue, and each server has an exponential service time with a mean rate of λ2 = 0.75 minutes.
3. After the ID/boarding-pass check, passengers are assigned to the shortest of the several personal-check queues. 
4. In the personal-check queues, they go through the personal scanner, and the processing time is uniformly distributed between 0.5 minutes and 1 minute.

## Simulation Overview

The simulation aims to model the flow of passengers through the airport security system. By building this simulation, we can experiment with different configurations of ID/boarding-pass checkers and personal-check queues to determine the optimal setup that minimizes average wait times.

## Simulation Parameters
Adjust the simulation parameters in the notebook to experiment with different scenarios. Key parameters include:

- Arrival rate (λ1)
- ID/boarding-pass check service rate (λ2)
- Personal-check service time range

## Results
After running the simulation, analyze the results to determine the optimal number of ID/boarding-pass checkers and personal-check queues needed to keep average wait times below X minutes.

## Dependencies
SimPy: A process-based discrete-event simulation library.
Statistics: Python module for statistical functions.
NumPy: Scientific computing library for arrays and matrices.
Pandas: Data manipulation and analysis library.
