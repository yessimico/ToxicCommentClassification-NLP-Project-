# Toxic Comment Classification (NLP)

## Overview
This project demonstrates an NLP pipeline for detecting toxic comments in Russian text with precision score 95%.
The model is based on TF-IDF and Logistic Regression.

## Data
- Text comments in Russian and there is file with dataset. Dataset was taken from kaggle
- Binary target: toxic / non-toxic

## Approach
- Text preprocessing with TF-IDF
- Logistic Regression classifier
- Hyperparameter tuning with GridSearchCV
- Evaluation using Precision, Recall, F1-score and PR-curve

## Results
- Optimized F1-score using GridSearchCV
- Improved recall by tuning decision threshold

## Technologies
- Python
- scikit-learn
- pandas, numpy
- matplotlib

## How to run
Open the notebook in Google Colab or Jupyter Notebook.
