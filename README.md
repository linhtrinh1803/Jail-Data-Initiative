# Comprehensive Criminal Justice Analysis
## Overview

This repository encompasses a thorough analysis of incarceration data, offering insights into various aspects of the criminal justice system. The analysis is presented through a series of Python scripts and Jupyter notebooks, each addressing specific facets of data cleaning, predictive modeling, and exploratory analysis. The goal is to provide a comprehensive understanding of incarceration dynamics, support informed decision-making, and contribute valuable insights for policymakers, researchers, and stakeholders.

## Data Cleaning
The Data Cleaning Python script is designed to preprocess and standardize a dataset containing information about individuals within the criminal justice system. It covers essential tasks such as column renaming, gender, race, eye color, hair color mapping, housing mapping, top charge mapping, height conversion, weight cleaning, bail and bond cleaning, date conversion, age calculation, and incarcerated days calculation. The script ensures consistency and enhances the data for further analysis.

## Analysis

The Analysis section is organized into three notebooks, each focusing on different aspects:

1. Incarcerated Days Notebook: Utilizes machine learning models and statistical analysis to predict and understand the duration of incarceration for individuals.
2. Duration out of Jails & Incarceration Counts Notebook: Primarily involves statistical analysis to explore and interpret quantitative aspects related to incarceration, such as counts, demographic breakdowns, or other numerical metrics.
3. Re-incarceration Notebook: Encompasses statistical analysis, machine learning models, and time series analysis to explore patterns of re-incarceration over time.
4. Dependencies for the analysis notebooks include pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, xgboost, and tensorflow.

## Detecting and Analyzing Overlapping Stays
The Python script in this section focuses on detecting overlapping stays within the same housing facility for inmates. It includes step-by-step instructions for data preparation, execution, parameter adjustments, and visualizations to identify and analyze instances of overlapping stays.

## XGBoost Model Tuning Notebook
This notebook specifically addresses the tuning of an XGBoost regression model for predicting the duration of incarceration. It employs a grid search approach to optimize hyperparameters, including max_depth, min_child_weight, and gamma. The notebook provides a systematic process for model tuning and evaluation, including visualizations of feature importance.

## Usage
1. Clone the repository to your local machine.
2. Follow the instructions in each script/notebook for data preparation and execution.
3. Customize parameters, mappings, and datasets based on your specific requirements.
4. Ensure that dependencies are installed using the provided commands.

## Important Notes
- Verify and adjust the mappings, dictionaries, and assumptions in the scripts based on your dataset.
- Customize the code as needed for your specific analysis goals.
- Ensure the input datasets are clean, well-formatted, and contain the required columns.

### Contributors
This repository and analysis were created by Brenda, Antonio, and Linh. Feel free to reach out for any questions or assistance.

Happy analyzing!
