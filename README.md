# Credit Card Approval Predictor

## Overview
This project involves building an automatic credit card approval predictor using machine learning techniques. The goal is to predict whether an individual's application for a credit card will be accepted or denied based on various features. The dataset used for this project is the Credit Card Approval dataset from the UCI Machine Learning Repository.

## Project Structure
The project is structured into several tasks, each addressing a specific aspect of the machine learning pipeline. The main tasks include:

1. **Loading and Inspecting the Dataset:**
   - Loading the credit card approval dataset.
   - Inspecting the dataset to understand its structure and characteristics.

2. **Inspecting the Applications:**
   - Analyzing the features of credit card applications.
   - Identifying numerical and non-numerical features, as well as missing values.

3. **Splitting the Dataset:**
   - Splitting the dataset into training and testing sets to prepare for machine learning modeling.

4. **Handling Missing Values (Part I):**
   - Replacing missing values with NaN for further processing.

5. **Handling Missing Values (Part II):**
   - Imputing missing values with mean imputation for numerical columns.
   - Imputing missing values with the most frequent values for categorical columns.

6. **Handling Missing Values (Part III):**
   - Completing the missing value treatment for remaining columns.

7. **Preprocessing the Data (Part I):**
   - Converting non-numeric data into numeric using one-hot encoding.

8. **Preprocessing the Data (Part II):**
   - Scaling feature values to a uniform range using Min-Max scaling.

9. **Fitting a Logistic Regression Model:**
   - Training a logistic regression model on the preprocessed data.

10. **Making Predictions and Evaluating Performance:**
    - Evaluating the model's accuracy and using a confusion matrix.

11. **Grid Searching and Model Improvement:**
    - Performing grid search to find optimal hyperparameters for the logistic regression model.

12. **Finding the Best Performing Model:**
    - Extracting the best model from the grid search and evaluating its performance.

## Usage
To run the project, follow these steps:
1. Ensure you have the required libraries installed (`pandas`, `numpy`, `scikit-learn`).
2. Clone the repository.
3. Execute the code in a Jupyter Notebook or any Python environment.

## Dependencies
- pandas
- numpy
- scikit-learn

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Credit Card Approval dataset: [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/credit+approval)


Feel free to contact: harshit2531937@gmail.com for any queries.
