
# Task 03 - Pipelines and Cross-Validation

## Project Overview
This project demonstrates a complete Machine Learning Pipeline using Python and Scikit-learn.

The Titanic dataset is used to predict passenger survival using Logistic Regression.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Seaborn
- Scikit-learn

## Project Implementation
1. Loaded and explored the Titanic dataset.
2. Separated input features and target variable.
3. Split data into training and testing sets.
4. Handled missing values.
5. Applied StandardScaler for numerical features.
6. Applied OneHotEncoder for categorical features.
7. Combined preprocessing and model using Pipeline.
8. Applied 5-Fold Stratified Cross-Validation.
9. Evaluated the final model using test accuracy.

## Data Leakage Prevention
All preprocessing steps are included inside the Machine Learning Pipeline.

Cross-validation is performed only on training data. The test dataset is kept separate until final evaluation.

## Expected Output
- Cross-validation scores
- Average CV accuracy
- Standard deviation
- Test accuracy
- Classification report

## How to Run
1. Open the notebook using Google Colab.
2. Run all cells in sequence.
3. View the cross-validation and test evaluation results.
