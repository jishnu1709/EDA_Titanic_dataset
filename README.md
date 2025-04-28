# EDA_Titanic_dataset
This repository contains an analysis of the Titanic dataset, focusing on Exploratory Data Analysis (EDA) to understand passenger demographics, survival rates, and potential factors influencing survival.

## Dataset Description

The Titanic dataset provides information about passengers aboard the RMS Titanic, including their age, gender, socio-economic class, and survival status. The key columns in the dataset are:

| Column | Description |
|---|---|
| PassengerId | Unique identifier for each passenger |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Passenger's name |
| Sex | Passenger's gender |
| Age | Passenger's age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Passenger fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |


## Data Cleaning and Preprocessing

The following steps were performed to clean and preprocess the data:

1. Missing values in the 'Embarked' column were replaced with the most frequent value, 'S'.
2. Missing values in the 'Age' and 'Cabin' columns were imputed using K-Nearest Neighbors (KNN) imputation.
3. The 'Cabin' column was preprocessed by extracting the deck information before imputation.

## Exploratory Data Analysis

EDA was conducted to uncover patterns and relationships within the data. Techniques used include:

- Descriptive statistics: Calculating mean, median, standard deviation, etc. for numerical variables.
- Data visualization: Creating histograms, box plots, scatter plots, and count plots to visualize data distributions and relationships.
- Correlation analysis: Examining the correlation between different variables.


## Key Insights

The analysis revealed several key insights, including:

1. Females had a significantly higher survival rate than males.
2. Passengers in higher classes (1st and 2nd) were more likely to survive.
3. Younger passengers, especially children, had a better chance of survival.
4. Traveling with family members offered a slight survival advantage, but large families had lower survival rates.
5. Embarkation port had a minor impact on survival, with Cherbourg passengers having a slightly higher rate.
6. Socio-economic status and gender played crucial roles in determining survival outcomes.
7. The overall survival rate was relatively low, highlighting the tragic nature of the event.


## Mean Values of Numerical Columns

| Column | Mean |
|---|---|
| Age | 29.7 |
| Fare | 32.2 |


## Conclusion

This EDA provides a comprehensive overview of the Titanic dataset, highlighting key factors related to passenger survival. Further analysis and predictive modeling can be performed based on these insights.
