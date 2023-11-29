# Titanic-Survivor-Prediction
## Overview
This project aims to analyze the Titanic dataset, available on Kaggle here. The primary objectives are to understand the dataset, perform necessary cleanup, and build a robust classification model to predict whether a passenger survives or not.

## Data Exploration and Preprocessing
I began by loading the dataset and exploring its structure:

The dataset comprises 891 entries and 12 columns.
Identified missing values in columns like 'Age,' 'Cabin,' and 'Embarked,' addressing them appropriately.
Descriptive statistics provided insights into the distribution of numerical features.


### Preprocessing steps included:

i. Dropped missing values in the 'Age' column.

ii.	Converting the 'Sex' column into dummy variables for better model compatibility.

iii.	Exploring relationships between variables through correlation analysis.

iv.	Exploratory Data Analysis

v.	Conducted exploratory data analysis (EDA) using visualizations to uncover patterns and insights:

## Gender Analysis:

Explored the distribution of passengers by gender.
Investigated the survival rate by gender, revealing a higher percentage of women surviving compared to men.


## Class Analysis:

Analyzed the distribution of passengers across different ticket classes.
Examined the survival rate by class, indicating variations in survival probabilities among different classes.


## Fare Analysis:

Explored the relationship between gender, fare, and survival.
Visualized the distribution of fares for both genders and their impact on survival.


## Machine Learning - Classification Model
I applied a classification model to predict survival based on various features:

-Selected features included 'Pclass,' 'Age,' 'SibSp,' 'Parch,' 'Fare,' 'Sex_female,' and 'Sex_male.'

-Split the data into training and testing sets.


## Model Building:
Utilized a robust classification algorithm (e.g., Random Forest, Logistic Regression).
Trained the model on the training data.


## Model Evaluation:
Evaluated the model's performance using appropriate metrics (accuracy, precision, recall, F1-score).
Fine-tuned the model if necessary for better results.


## Conclusion
This project provides a comprehensive analysis of the Titanic dataset, addressing missing values, exploring relationships, and building a predictive model for passenger survival. The classification model aims to contribute accurate predictions based on relevant features. The insights gained from this project can be valuable for understanding the factors influencing survival on the Titanic.
