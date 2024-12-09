# Detroit-Subway-Optimization
Final project with Annapurni Subramanian and Michelle Zhou for the 15.C57 Optimization Methods class with Professor Alexandre Jacquillat at MIT. Dec 9th, 2024.

In this project, we used prescriptive Mixed Integer Optimization to design a potential subway line for the city of Detroit, MI. This involved a two stage process. First, 25 stations were optimally placed in the city of Detroit to minimize the total distance from the population to subway stations. Then, considering these 25 stations, a network flow formulation connects stations to minimize total distance travelled as the population commutes from their home stations to their work stations. The data comes from the US Census Bereau, and the optimization is done in Julia (using JuMP and Gurobi). 

This repository includes an 9 page final paper outlining methodology and results, a short presentation, the code (written in python and Julia) used to clean the data, create the optimization formulations and make the visualizations, along with the data CSV files. If you have any questions or are interested in the process, data, formulations, code, or analysis, please do not hesitate to reach out!
