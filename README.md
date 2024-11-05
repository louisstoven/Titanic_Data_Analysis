# Titanic Dataset Analysis
## Overview
This notebook presents an exploratory data analysis (EDA) of the Titanic dataset, which contains information on passengers aboard the RMS Titanic, including whether they survived the disaster. The goal of this analysis is to identify patterns and factors that influenced survival rates, using a combination of descriptive statistics, data visualization, and basic statistical methods.

## Data Description
The Titanic dataset contains 891 rows and 12 columns, including:

PassengerID: Unique identifier for each passenger
Survived: Indicates survival status (1 = Survived, 0 = Did not survive)
Pclass: Passenger class (1st, 2nd, or 3rd)
Name, Sex, Age: Basic demographic information
SibSp, Parch: Number of siblings/spouses and parents/children aboard
Ticket, Fare: Ticket number and fare paid
Cabin, Embarked: Cabin number and embarkation port
## Analysis Sections
Data Inspection and Cleaning
Overview of data structure, missing values, and handling of null values.
Exploratory Data Analysis (EDA)
Visual analysis of survival rates based on features like class, age, gender, and family relationships.
Histograms, count plots, and box plots used to reveal distribution patterns and outliers.
Categorical Survival Analysis
Survival rates by categorical features (e.g., gender, passenger class, and embarkation port).
Numerical Survival Analysis
Analysis of fare and age distributions and their relationship to survival rates, including outlier examination.
Limitations and Observations
Discusses data quality issues, missing information, and the limitations of historical data.
## Key Findings
Women and children were more likely to survive than men.
Passengers in 1st class had a higher survival rate than those in lower classes.
Passengers embarking from certain ports had differing survival rates.
## Requirements
The following Python libraries are used in this notebook:

Pandas: For data manipulation
Seaborn & Matplotlib: For data visualization
NumPy: For numerical operations
Make sure to install these libraries if they’re not already available in your environment.


