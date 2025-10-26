## Project Overview
Predicting flight delays through the application of machine learning is the main objective of this project. A classification model is to be developed that will be able to indicate whether a flight would be delayed by at least 15 minutes or not, taking into account various flight characteristics, temporal factors, and airline information.

## Business Problem
The delay predictions during flight booking are to be offered by travel booking websites as an enhancement to the customer's journey. The model assists the customers in better travel planning by enlightening them with the possible delays.

## Dataset
- **Source**: Bureau of Transportation Statistics (BTS) Airline On-Time Performance Data
- **Period**: 2014-2018
- **Size**: 60 compressed files, with each file containing monthly flight data
- **Coverage**: Domestic flights in the US involving major airlines and airports only
## What to Expect When Running the Code
Phase 1: Data Preparation
-Automatic download and extraction of flight data
-Data cleaning and null value handling
-Feature selection and filtering for top airports/airlines
-Creation of target variable (is_delay)

Phase 2: Exploratory Data Analysis
-Visualization of delay patterns by month, day, hour, airline, and airport
-Analysis of delay causes and correlations
-Statistical summaries and distribution plots

Phase 3: Feature Engineering
-Categorical variable encoding (one-hot encoding)
-Temporal feature extraction
-Creation of DepHourofDay from scheduled departure time
-Dataset splitting (Train/Validation/Test: 64%/16%/20%)

Phase 4: Model Training & Evaluation
-Baseline Logistic Regression model
-Performance metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
-Confusion matrix visualization
-Feature importance analysis

Expected Results
-Baseline model performance: accuracy, recall, precision
-Insights into which factors most influence flight delays
-Foundation for model improvement in subsequent iterations
