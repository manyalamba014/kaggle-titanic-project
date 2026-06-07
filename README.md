# Titanic Survival Prediction

This project builds a machine learning model to predict passenger survival from the Kaggle Titanic dataset.

## Overview

The notebook walks through an end-to-end classification workflow: loading the training and test datasets, cleaning missing values, engineering predictive features, training a Random Forest model, evaluating performance, and generating a submission file for Kaggle.

## What This Project Does

- Cleans and preprocesses Titanic passenger data
- Engineers features such as family size, solo traveler status, passenger title, age bins, fare bins, and cabin availability
- Converts categorical variables into model-ready numerical features
- Trains a Random Forest Classifier using scikit-learn
- Evaluates model accuracy using cross-validation and validation splits
- Generates survival predictions for the test dataset

## Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- Jupyter Notebook

## Project Structure

```text
titanic-survival-prediction/
├── notebooks/
│   └── titanic_survival_prediction.ipynb
├── src/
│   └── titanic_model.py
├── data/
│   └── .gitkeep
├── requirements.txt
├── .gitignore
└── README.md
```

## How to Run

1. Clone this repository.
2. Download the Titanic `train.csv` and `test.csv` files from Kaggle.
3. Place the CSV files in the project folder or update the file paths in the notebook.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Open the notebook and run all cells:

```bash
jupyter notebook notebooks/titanic_survival_prediction.ipynb
```

## Skills Demonstrated

- Data cleaning
- Feature engineering
- Classification modeling
- Model evaluation
- Machine learning workflow design
- Kaggle submission generation

## Short Description

Developed a machine learning model to predict Titanic passenger survival using feature engineering, data preprocessing, and Random Forest classification in Python.
