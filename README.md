# Classification of Down Syndrome in Mice Using Gene Expression Data

## Overview

This repository contains code and documentation for a project focused on classifying Down syndrome in mice based on gene expression data. The project includes data preprocessing, model training and validation, and feature selection to improve classification performance.

## Dataset

The dataset used for this project is from the UCI Machine Learning Repository:
- **Dataset**: [Mice Protein Expression](https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression#)
- **Description**: This dataset includes gene expression measurements from various proteins, and the target variable is the genotype indicating the presence or absence of Down syndrome.

## Project Objectives

1. **Data Preprocessing**:
   - Handle missing values using feature imputation.
   - Perform necessary data transformations and scaling.

2. **Model Training and Validation**:
   - Train and validate the following models:
     - **Random Forest**
     - **Support Vector Machine (SVM) with RBF Kernel**
     - **Neural Network** with a single hidden layer
   - Tune hyperparameters to optimize model performance.

3. **Feature Selection**:
   - Use recursive feature elimination (RFE) to identify and remove less important features, thereby improving model performance.

## Note: You will find wine_quality_pridiction.ipynb file in this repository which has more than the necessary information. Question 2 contains the solution described above.


