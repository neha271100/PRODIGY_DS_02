# PRODIGY_DS_02
# Task 02: Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic Dataset

## Overview
This project is part of the Data Science Internship Program at Prodigy InfoTech. The goal of this task is to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The task involves exploring relationships between variables, identifying patterns, and uncovering trends in the data.

### Task Details
#### Objective:
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

#### Sample Dataset:
The dataset used for this task is sourced from Kaggle: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data).

## Dataset Information
### 1. Gender Submission Data
- **Source:** gender_submission.csv
- **Description:** A file that provides a baseline gender-based model to predict survival.
#### Key Columns:
- **PassengerId:** The ID of the passenger.
- **Survived:** Whether the passenger survived (1) or not (0).

### 2. Training Data
- **Source:** train.csv
- **Description:** The training dataset containing features like age, sex, class, etc., and the target variable `Survived`.
#### Key Columns:
- **PassengerId:** The ID of the passenger.
- **Survived:** Whether the passenger survived (1) or not (0).
- **Pclass:** The class of the passenger (1st, 2nd, 3rd).
- **Name:** The name of the passenger.
- **Sex:** The gender of the passenger.
- **Age:** The age of the passenger.
- **SibSp:** Number of siblings/spouses aboard the Titanic.
- **Parch:** Number of parents/children aboard the Titanic.
- **Ticket:** The ticket number.
- **Fare:** The fare paid by the passenger.
- **Cabin:** The cabin number.
- **Embarked:** The port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

### 3. Test Data
- **Source:** test.csv
- **Description:** The test dataset with similar features, used for testing model predictions.
#### Key Columns:
- **PassengerId:** The ID of the passenger.
- **Pclass:** The class of the passenger (1st, 2nd, 3rd).
- **Name:** The name of the passenger.
- **Sex:** The gender of the passenger.
- **Age:** The age of the passenger.
- **SibSp:** Number of siblings/spouses aboard the Titanic.
- **Parch:** Number of parents/children aboard the Titanic.
- **Ticket:** The ticket number.
- **Fare:** The fare paid by the passenger.
- **Cabin:** The cabin number.
- **Embarked:** The port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Visualizations
### 1. Univariate Analysis
- **Histograms:**
  - Distribution of age.
  - Distribution of fare.
- **Bar Charts:**
  - Distribution of passengers across different classes.
  - Survival rate based on gender.

### 2. Bivariate Analysis
- **Bar Charts:**
  - Survival rate based on passenger class.
  - Survival rate based on port of embarkation.
- **Scatter Plots:**
  - Age vs. Fare, colored by survival.

### 3. Multivariate Analysis
- **Heatmaps:**
  - Correlation between numerical variables.
- **Pair Plots:**
  - Pairwise relationships in the dataset.

## Libraries Used
- **pandas** for data manipulation.
- **matplotlib** and **seaborn** for data visualization.
- **numpy** for numerical operations.
- **zipfile** and **os** for file handling.

## Acknowledgments
- **Kaggle:** For providing the Titanic dataset.
- **Prodigy InfoTech:** For the opportunity to work on this project as part of the Data Science Internship Program.
