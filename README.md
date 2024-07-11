# Data-Science-project---Student-Performance-
***
Analyze student performance with a dataset of 1,000 entries including demographics, educational background, and test scores. Features total and average scores, uses regression models (Linear, Lasso, Ridge, KNN, Decision Tree, Random Forest, XGB, CatBoost, AdaBoost), and data visualizations to explore performance factors.
data link: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams


## Student Performance Data Analysis
This repository contains a comprehensive dataset and analysis of student performance, using various regression models and extensive data visualization techniques. The dataset includes 1,000 entries with 8 attributes related to demographics, educational background, and test scores.

## Dataset Overview
The dataset consists of the following columns:

* gender: Gender of the student (categorical: 'male', 'female')
* race/ethnicity: Ethnic background of the student (categorical: five levels)
* parental level of education: Highest level of education attained by the student's parents (categorical: 'high school', 'some college', 'associate's degree', 'bachelor's degree', 'master's degree')
* lunch: Type of lunch received (categorical: 'standard', 'free/reduced')
* test preparation course: Whether the student completed a test preparation course (categorical: 'none', 'completed')
* math score: Score in mathematics (numerical: 0-100)
* reading score: Score in reading (numerical: 0-100)
* writing score: Score in writing (numerical: 0-100)
* total score: Sum of math, reading, and writing scores (numerical: 0-300)
* average score: Average of math, reading, and writing scores (numerical: 0-100)

## Project Goals
The main objectives of this project are:

*To analyze the impact of demographic factors and parental education on student performance.
*To explore the correlation between different test scores.
*To assess the effect of test preparation on performance.
*To compare the performance of various regression models in predicting student scores.
*To create new features to enhance the analysis.
*Regression Models Used

## The following regression models were implemented and compared:

*Linear Regression
*Lasso
*Ridge
*K-Neighbors Regressor
*Decision Tree
*Random Forest Regressor
*XGBRegressor
*CatBoosting Regressor
*AdaBoost Regressor
*Tools and Technologies
*Pandas: For data manipulation and analysis.
*Matplotlib/Seaborn: For data visualization.
*Scikit-learn: For implementing and comparing regression models.
*XGBoost: For implementing the XGBRegressor.
*CatBoost: For implementing the CatBoosting Regressor.


## Project Structure
*Data Exploration: Initial examination of the data to understand its structure and main characteristics.
*Visualization: Creating plots and charts to visually represent the data and findings.
*Data Cleaning: Handling missing values and outliers, and preparing the data for analysis.
*Feature Engineering: Creating new features such as total score and average score.
*Statistical Analysis: Analyzing the relationships and correlations between different variables.
*Model Implementation and Comparison: Implementing various regression models and comparing their performance.

## Contribution
Feel free to fork this repository and submit pull requests. Contributions are welcome!
