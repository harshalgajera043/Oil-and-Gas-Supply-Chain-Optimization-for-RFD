# Oil-and-Gas-Supply-Chain-Optimization-for-RFD

This project aims to optimize the end-to-end cycle of oil processing within Rock Flow Dynamics, a key player in the Oil and Gas sector. By leveraging analytical methods and modeling techniques, the objective is to make strategic decisions in transporting oil, considering three distinct options available for oil transportation.

# Introduction
Rock Flow Dynamics operates across upstream, midstream, and downstream phases, facing challenges in fluid production, transportation, and processing. The project focuses on maximizing operational profit by identifying the most effective mode of transport and optimizing the movement of resources between different locations.

# Objective
The primary objective is to maximize operational profit by optimizing the end-to-end cycle of oil processing. This involves determining the fraction of oil to be transported from production locations to processing locations via the most efficient mode of transport. The project integrates various optimization techniques and considers the capabilities and efficiencies associated with transportation types and processing locations.

# Dataset
## Problem Understanding
The dataset includes details about fluid production capacities, production costs, distances between production and processing locations, transportation options (truck, train, pipeline), and downstream processing capacities and costs.

## Data Overview
Upstream Level: Fluid production details for three locations.
Midstream Level: Transportation distances and options (Truck, Train, Pipeline).
Downstream Level: Processing capacities, efficiencies, and costs.

#  Model Setup
## Modelling Objective
The objective is to maximize operational profit by optimizing the end-to-end cycle of oil processing. Decision variables involve determining the fraction of production to be transported from each production location to processing locations via different transportation modes.

## Constraints
1. Ensuring transport if all produced fluid.
2. Limiting transported fluid to processing capacity.
3. Fraction of production being transported should not exceed 50%.
4. Non-negative constraints.
5. Total transportation from each location to another should not exceed 20%.

# Results
## Decision Variable Output
The transportation table outlines the optimal fraction of production to be transported using Truck, Train, or Pipeline between different locations.

## Model Results
The model results indicate the profit generated, with a detailed breakdown of selling revenue for each outcome (sulfur, water, natural gas, crude oil) in different processing locations.

# Recommendation
The project recommends the most efficient transportation modes and routes for maximizing profit. Specific suggestions include utilizing pipelines for optimal efficiency and identifying preferred routes for each production and processing location.
