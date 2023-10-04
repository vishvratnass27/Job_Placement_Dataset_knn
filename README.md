# Job Placement Data Analysis and Classification

## Overview
This repository contains Python code for performing data analysis and classification on a job placement dataset. The dataset includes various attributes related to students and their job placement status. The analysis and classification tasks involve data visualization, data preprocessing, and using the K-Nearest Neighbors (KNN) algorithm for classification.

## Getting Started

## Code Structure
- `job_placement_analysis.py`: The main Python script that performs data analysis and classification on the dataset.
- `Job_Placement_Data.csv`: The dataset containing information about students and their job placement status.
- `README.md`: This README file providing an overview of the repository.

## Analysis and Visualization
The code includes various data visualization techniques using libraries such as Matplotlib and Seaborn to explore the dataset. Key visualizations include:
- Countplots to analyze categorical variables and their relationship with job placement status.
- Pie charts to visualize the distribution of various categorical variables.
- Pair plots and box plots to examine the distribution of numerical features.

## Data Preprocessing
- Label encoding is applied to convert categorical variables into numerical format.
- Dummy variables are created for categorical attributes with multiple categories.
- The dataset is split into training and testing sets using the `train_test_split` function.

## Classification
- The K-Nearest Neighbors (KNN) algorithm is used for classification.
- The code trains the KNN model on the training data and makes predictions on the test data.
- Evaluation metrics such as accuracy, precision, recall, and F1 score are computed and displayed.

## Results
The code provides insights into the dataset, including visualizations of feature distributions and correlations. It also offers a classification model to predict job placement status based on the given attributes.

Feel free to explore the code and dataset to gain a better understanding of job placement trends and the factors that influence job placement outcomes.

