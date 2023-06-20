[![author](https://img.shields.io/badge/author-lauradefaria-purple.svg)](https://github.com/lauradefaria)
[![author](https://img.shields.io/badge/author-eduardovegas-black.svg)](https://github.com/eduardovegas) 

# CVRP_With_AI

The objective is to cluster instances from the literature and identify those similar to the studied article to gain knowledge about the set of high-quality instances available in the literature. It will assist in evaluating future algorithms that benchmark with these instances. For more comprehension, watch our video explanation on <a href="https://youtu.be/f8cNibOlVPU">Youtube</a>.

---

## Table of Contents
- [CVRP (Capacitaded Vehicle Routing Problem)](#cvrp-(capacitaded-vehicle-routing-problem))
- [Benchmarks](#benchmarks)
- [Data](#data)
- [Setup](#setup)
- [Clone](#clone)
- [Author](#author)

---    
## CVRP (Capacitaded Vehicle Routing Problem)

Vehicle routing problem (VRP) is a combinatorial and integer programming which ask “What is the optimal set of routes for a fleet of vehicles in order to deliver to a given set of customers?” It generalizes the well-known traveling salesman problem (TSP). The capacitated vehicle routing problem (CVRP) is a VRP in which vehicles with limited carrying capacity need to pick up or deliver items to various locations. The items have a quantity, such as weight or volume, and each vehicle has a maximum capacity that they can carry. The problem is to pick up or deliver the items with the least cost, while never exceeding the capacity of the vehicles.

<h1 align="center">
  <img src="https://github.com/lauradefaria/CVRP_With_AI/blob/main/imgs/cvrp.png">
</h1>

---    
## Benchmarks

In operations research, benchmarks can be used to evaluate the performance of different strategies, algorithms, or models. By comparing the performance of different approaches against established benchmarks, researchers can assess their effectiveness and identify areas for improvement. This allows for evidence-based decision-making and optimization of processes.

---    
## Data

We used Data from the article based on Brechmark and the Capacitated Vehicle Routing Problem Library
  - The <a href="https://repub.eur.nl/pub/116701#:~:text=New%20benchmark%20instances%20for%20the%20capacitated%20vehicle%20routing,lack%20of%20a%20good%20set%20of%20benchmark%20instances">article</a>. proposes a new set of 100 instances ranging from 100 to 1000 customers, designed in order to provide a more comprehensive and balanced experimental. To have a greater discriminating ability to identify “which algorithm is better”, the new benchmarks should also allow for a deeper statistical analysis of the performance of an algorithm. In particular, they will enable one to investigate how the characteristics of an instance affect its performance.
  - The instances of literature were extracted through the <a href="http://vrp.atd-lab.inf.puc-rio.br/index.php/en/">CVRPLIB</a> website, generating a dataset of 3,000 instances. General data was obtained by analysing the instances, obtaining information such as customer demand, positioning in the plan, and possible customer clusters.The majority of the preprocessing was performed manually, applying only dimensionality reduction to the code.  The Dataset is located in the <a href="https://github.com/eduardovegas/CVRP_DATA">CVRP_DATA</a>. repository.

---    
## Setup

Just open the directory cloned path in terminal and run
```shell
!pip install -U pandas-profiling
!pip install -U yellowbrick
!pip install hdbscan
!pip install ydata_profiling
```
    
---    
## Clone

- Clone this repo to your local machine using
    > https://github.com/lauradefaria/CVRP_With_AI.git

---
## Authors

|<a href="https://www.linkedin.com/in/lauradefaria/" target="_blank">**Laura de Faria Maranhão Ayres**</a> | <a href="https://linkedin.com/in/eduardovegas" target="_blank">**Eduardo Luiz Araujo dos Santos**</a>      |
|:-----------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------:|
|                   <img src="https://github.com/lauradefaria/CVRP_With_AI/blob/main/imgs/laura.png" width="200px"> </img>                            |               <img src="https://github.com/lauradefaria/CVRP_With_AI/blob/main/imgs/eduardo.jpg" width="200px"> </img>                          
|               <a href="http://github.com/lauradefaria" target="_blank">`github.com/lauradefaria`</a>      |  <a href="https://github.com/eduardovegas" target="_blank">`github.com/eduardovegas`</a>  |
