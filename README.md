# Sonar Data Classification

This project aims to classify sonar signals as either bouncing off a metal cylinder ('M') or a rock ('R') using a Logistic Regression model.

## Dataset

The dataset used in this project is the Sonar dataset, which contains 208 entries, each with 60 numerical features representing the sonar signal and a target variable indicating whether the object is a metal cylinder or a rock.

## Project Steps

1.  **Load Data**: The sonar data is loaded from a CSV file into a pandas DataFrame.
2.  **Data Exploration**: Initial data exploration is performed to understand the structure and characteristics of the dataset, including checking the head of the DataFrame, its shape, and the distribution of the target variable.
3.  **Data Preparation**: The data is split into features (X) and the target variable (Y).
4.  **Train-Test Split**: The dataset is split into training and testing sets to evaluate the model's performance on unseen data. A test size of 10% is used with stratification based on the target variable to maintain the proportion of classes in both sets.
5.  **Model Training**: A Logistic Regression model is initialized and trained on the training data.
6.  **Model Evaluation**: The trained model is evaluated on both the training and testing sets to assess its accuracy.

## Results

The accuracy of the Logistic Regression model on the training data is: 0.8342245989304813
The accuracy of the Logistic Regression model on the test data is: 0.7619047619047619
