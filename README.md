# ShopSmart – Purchase Prediction

## Overview

This project predicts whether a visitor will make a purchase on an e-commerce website based on their browsing session behavior.

## Dataset

The dataset contains **12,330 user sessions** with features such as:

* Product-related pages visited
* Page values
* Bounce rate
* Exit rate
* Month of visit
* Visitor type

**Target variable:** `Revenue` (Purchase / No Purchase)

## Model

* Decision Tree Classifier
* Preprocessing using **ColumnTransformer**
* Hyperparameter tuning with **GridSearchCV**

## Evaluation

The model was evaluated using **F1 Score** because the dataset is imbalanced.

**Best F1 Score:** 0.64

## Tools

Python, Pandas, Scikit-learn, Matplotlib, Jupyter Notebook
