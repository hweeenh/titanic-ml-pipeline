# Titanic ML Prediction

A hands-on machine learning project using the Titanic dataset.

## Project Overview 

This project is being built alongside my study of **scikit-learn**, with a focus on understanding rather than simply producing a Kaggle submission. The goal is to predict passenger survival from passenger attributes using a reproducible preprocessing and modelling pipeline.

## Learning Goals

* Understand scikit-learn workflows
* Learn `Pipeline`
* Learn `ColumnTransformer`
* Understand preprocessing and feature transformation
* Train and evaluate classification models
* Apply these concepts to a real dataset
* Produce a final submission for the Titanic Kaggle competition

## Project Progress

* [x] Set up GitHub and local development environment
* [x] Learn basic scikit-learn Pipeline
* [x] Learn ColumnTransformer
* [x] Combine Pipeline + ColumnTransformer
* [x] Explore the Titanic dataset
* [x] Build preprocessing pipeline
* [x] Train classification model
* [x] Evaluate model
* [x] Generate Kaggle submission

## Models Explored

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- Suppoer Vector Machine (SVM)

## Evaluation and Experiments

A fixed train-validation split was used to compare model performance reproducibly and explored hyperparameters for tree-based models. Feature importance was also investigated using model's built-in feature importance, permutation importance, and SHAP explanations.

Feature Engineering experiments tested adding Title, FamilySize, IsAlone, AgeGroup and Deck features independently against the XGBoost baseline to monitor changes in validation accuracy and Kaggle scores.

## Project Structure

```text
titanic-ml-prediction/
├── README.md
├── .gitignore
├── data/              # Local datasets, not tracked by Git
└── ...
```

## Tools

* Python
* scikit-learn
* pandas
* NumPy
* Git / GitHub
* VS Code
* Kaggle

## Learning Summary

I learned to distinguish validation accuracy from Kaggle score performance, and to interpret feature importance as model behaviour rather than evidence of causation. 

## Limitations

The experiments use a single fixed train-validation split, without cross-validation. Small score differences may not generalise.

## Notes

This repository also serves as a learning log. Code will be developed progressively while studying the underlying scikit-learn concepts.
