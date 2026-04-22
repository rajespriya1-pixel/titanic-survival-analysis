# Titanic Survival Analysis

## Project Overview

This project analyzes the Titanic passenger dataset to identify the factors that influenced passenger survival. The analysis focuses on understanding how features such as gender, passenger class, age, fare, and family size affected survival chances.

## Objective

To explore the Titanic dataset, identify patterns in passenger survival, and generate insights based on demographic and travel-related factors.

## Dataset Information

* **Rows:** 891
* **Columns:** 12

### Features Used

* **PassengerId** – Unique passenger ID
* **Survived** – Survival status (0 = No, 1 = Yes)
* **Pclass** – Passenger class
* **Sex** – Gender
* **Age** – Passenger age
* **SibSp** – Number of siblings/spouses aboard
* **Parch** – Number of parents/children aboard
* **Fare** – Ticket fare
* **Embarked** – Port of embarkation
* **Family_size** – Total family members aboard

## Data Cleaning

* Missing values in **Age** were filled with mean values.
* **Cabin** column was removed due to excessive missing values.
* Missing values in **Embarked** were filled using mode.
* Created a new feature: **Family_size**
* Applied log transformation to reduce skewness in fare-related features.

## Exploratory Data Analysis

The analysis includes:

* Survival rate by gender
* Survival rate by passenger class
* Survival rate by age group
* Survival rate by family size
* Fare distribution analysis
* Combined analysis of gender and passenger class

## Key Insights

* Females had a significantly higher survival rate than males.
* First-class passengers had better survival chances than lower classes.
* Children had higher survival rates, while seniors had the lowest.
* Small families had better survival chances than large families.
* Wealthier passengers had better access to survival opportunities.

## Conclusion

Survival was strongly influenced by gender, passenger class, age, fare, and family size. Female passengers, children, and first-class passengers had the highest survival rates, showing that demographic and socio-economic factors played a major role in survival outcomes.
