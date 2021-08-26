# Quick Summary
This project is about classifying the activity of a vessel based on sequence of vessel position and a few vessel data.

# Main Components
There are three main components in this project
1. Data Preparation
2. Model Training
3. Simulation

# Data Preparation
Data preparation is related to data cleaning and data transformation.
For instance, this component does the calculation of hour_since, mile_since, previous coordinate and etc. Also some data cleansing and resizing the datatype to optimize the later training. 


# Model Training
This component also consists of few tranformation which is related to data aggregation and calculation of some indicators to help the model recognize the pattern later. For instance, distance_ratio and period_total_distance. 
After that, then the model training will follow. There are more than one model training in this component.

# Simulation
In this component, the process will simulate how to use a trained machine learning model using new data. This component will produce an excel file that consists of the classification.


# Library installation
- Install Python (at least version 3.7)
- `pip install -r requirements4.txt`
