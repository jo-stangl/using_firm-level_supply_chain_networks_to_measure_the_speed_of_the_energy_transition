# using_firm-level_supply_chain_networks_to_measure_the_speed_of_the_energy_transition

This repository contains the scripts that implement the methodology presented in the manuscript by Stangl et al. "Using firm-level supply chain networks to measure the speed of the energy transition". These scripts demonstrate key techniques and concepts from the paper, providing a practical example for further exploration and replication. Datasets used in the paper are confidential, hence we demonstrate the methodology on dummy datasets.

create_toy_network.ipynb: initializes annual snapshots of a dummy supply chain network for the years 2020-2024

estimate_energy_consumption_and_electricity_growth.ipynb: estimates annual consumption of oil, gas and electricity for all firms using the dummy networks and annual energy prices; also estimates decarbonization trends and decarbonization rates for every firm

FIG2_heterogeneity.ipynb: produces a plot like Figure 2 of the accompanying manuscript

FIG3_difference_transitioning_non-transitioning_firms.ipynb: produces a plot like Figure 3 of the accompanying manuscript; also implements the multivariate logistic regression on firm variables

FIG4_scenarios.ipynb: produces a plot like Figure 4 of the accompanying manuscript; also implements the nearest-neighbour-matching of transitioning and non-transitioning firms

