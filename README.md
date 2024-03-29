# Route planner with A* algorithm (python)
- This is the project from [Udacity's Introduction to Self-Driving Cars Nanodegree Program](https://learn.udacity.com/nanodegrees/nd113).
- The code was developed based on the assignment from the Nanodegree program. 
- The assignment was to code a route-planning algorithm, A*, like the one used in Google Maps.

---

## Project Overview
### Goals
* Implement A* algorithm to find shortest distance given a start and goal node.
* Allow users to define choose two types of maps (10 nodes and 40 nodes) and to select the start and goal node.

### Structures
This project consists of three files:
* `helpers.py`: this code helps to load map data, defining map objects, and display maps.
* `route_planner.ipynb`: implementation of A* algorithm.

### Run the code
To run the code:
1. Clone this respository: https://github.com/lucassuryana/route_planner.git 
2. Open route_planner.ipynb
3. Run all chunks

### Dependencies
This project needs following dependencies:
* networkx >= 2.7.1
* plotly >= 5.6.0
* python >= 3.9.12

### Results
1. If we choose map of 40 nodes with start node as 5 and end end node as 34. The black and yellow nodes respectively denote the start and goal node. To see the interactive plot, download this [html file](/html/5_to_34.html) and open in your own browser.
![GitHub Logo](/figures/5_to_34.png)
2. If we choose map of 40 nodes with start node as 10 and end end node as 30. The black and yellow nodes respectively denote the start and goal node. To see the interactive plot, download this [html file](/html/10_to_30.html) and open in your own browser.
![GitHub Logo](/figures/10_to_30.png) 