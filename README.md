# Analysis-and-Prediction-of-Hate-Crimes-Using-2016-U.S.-Election-Data
Analyzed hate crime data around the 2016 U.S. elections using machine learning techniques. Built models to explore relationships between income inequality, race, population factors, and hate crime rates, while comparing FBI and SPLC data trends across states
# Project Overview
This project analyzes the relationship between socio-economic factors, demographic data, and the prevalence of hate crimes in U.S. states following the 2016 U.S. election. Using data sourced from the Southern Poverty Law Center (SPLC) and the FBI, this project explores how income inequality, race, and other factors relate to hate crime incidents, and builds predictive models to understand the patterns and correlations in the dataset.
# Dataset
![Screenshot 2024-09-18 at 6 09 29 PM](https://github.com/user-attachments/assets/e085cce8-f873-4b7e-b506-4245c374fc4a)

# Objectives
Correlation Analysis: Investigate how income inequality (Gini Index) correlates with the number of hate crimes reported.
Predictive Modeling: Build predictive models to estimate hate crime incidents based on socio-economic and racial demographics.
State-Wise Analysis: Explore variations in hate crimes across states and find similarities in hate crime incidents between states.
Comparative Analysis: Compare hate crime data from SPLC (post-election) with FBI data (pre-election).
# Methodology
Data Preprocessing:
Handle missing values and impute where necessary.
Perform data cleaning to convert non-numeric values where appropriate.
# Correlation Analysis:
Calculate Pearson and Spearman correlation coefficients to explore relationships between income inequality and hate crimes.
Simple linear regression to model the relationship between the Gini index and hate crime rates.
#  Predictive Modeling:
Use linear regression to predict hate crimes per 100,000 people based on the share of the non-white, non-citizen, and white poverty populations.
# State-Wise Comparison:
Perform descriptive analysis and use visualizations (box plots) to compare hate crimes across states.
Identify states with similar hate crime rates using correlation analysis between SPLC and FBI data.
# Results
Correlation: There is a moderate positive correlation (0.338) between income inequality and hate crime rates according to the SPLC data, while the Spearman correlation shows a weak monotonic relationship (-0.052).
Predictive Model: The linear regression model, based on race and population demographics, predicted hate crime rates with a Mean Squared Error (MSE) of 0.0399, showing reasonably good predictive power.
State-Wise Analysis: States such as Colorado, Maryland, New York, and Virginia showed similar ranges in hate crime incidents when comparing SPLC and FBI data.
# Visualizations
Correlation Heatmaps
Boxplots comparing hate crimes per 100,000 people (SPLC vs. FBI)
Scatter plots for linear regression fits
![image](https://github.com/user-attachments/assets/24c40b63-42b6-495e-9903-3ed1dd25394e)
# Conclusion
This project provides insights into the relationship between socio-economic factors and hate crime rates, as well as predictive models that can estimate hate crime incidents based on race and demographic data. The results underscore the importance of income inequality and demographic diversity in understanding the trends in hate crime occurrences.

# Acknowledgments
The dataset is sourced from the Southern Poverty Law Center and the FBI and was compiled by FiveThirtyEight.
