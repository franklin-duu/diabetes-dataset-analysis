# Diabetes Analysis

Franklin Du

## Description

DATASET: Comprehensive Diabetes Clinical Dataset(100k rows)

SOURCE: https://www.kaggle.com/datasets/priyamchoksi/100000-diabetes-clinical-dataset

DESCRIPTION: 100,000 Diabetes Dataset for Predictive Modeling and Health Analytics

This project will use this 100k diabetes dataset to analyze any possible trends between diabetes and several different variables within the dataset. The variables that will be analyzed are: where the individual lives, their race, their hypertension, possible heart disease, smoking history, bmi, and blood glucose levels. The data will first be cleaned and condensed, reducing the race columns into a singular column and dealing with any missing data. Then each variables will be compared to the diabetes column using the corresponding tests to see if there is any correlation between those variables and whether or not the individual has diabetes.

### DATA DICTIONARY:
- year: The year the data was collected
- gender: The gender of the individual
- age: The age of the individual
- location: state or region the individual resides
- race:AfricanAmerican: Binary indicator (0 or 1)
- race:Asian: Binary indicator (0 or 1)
- race:Caucasian: Binary indicator (0 or 1)
- race:Hispanic: Binary indicator (0 or 1)
- race:Other: Binary indicator (0 or 1)
- hypertension: Binary indicator (0 or 1)
- heart_disease: Binary indicator (0 or 1)
- smoking_history: The individual's smoking history (never/current/former)
- bmi: Body mass indes of the individual
- hbA1c_lev: The HbA11c (a measure of blood sugar levels over time)
- blood_glucose_level: The blood glucose level in mg/dL
- diabetes: Binary indicator (0 or 1)

### INITIAL QUALITY AUDIT:
- Rows: 100k
- Columns: 16
- No Null or Missing values
- Data types: 13 numeric, 3 object
- Duplicates: 14 duplicates
- Outliers:
- Some outliers in BMI, hbA1c level, blood glucose level.

## Project Outline

### Interface Plan

The data will come from kaggle and analyzed using python and Jupyter notebooks.

### Data collection and Storage Plan

The data will be loaded in using the provided .cvs, intermediate files will be stored as .parquet to maximize space and time efficiency since this project will be working with a lot of data.

### Data Analysis and Visualization Plan

As previously mentioned, the data will be analyzed by seeing the possible correlation between diabetes and the other variables in the dataset. Each test will also have accompanying visualization like bar graphs or histograms to make the correlation more visible. 