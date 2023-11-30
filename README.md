# Tor and Non-Tor Classification

## Overview

This project aims to classify network traffic into two categories: Tor and Non-Tor. Tor is an anonymity network that allows users to access the internet while concealing their identity, making it crucial to identify Tor traffic for various security and monitoring purposes.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)

## Dataset

### Data Source

The dataset used for this project is derived from canadian institute of cybersecurity-2020. It includes labeled network traffic data where each sample is marked as either "Tor" or "Non-Tor."

### Data Preprocessing

Preprocessing steps performed on the dataset, such as data cleaning, feature extraction, and label encoding 
  -As the label consist of NonTOR and TOR label set we will first convert it into zero or one class only.
  -As we are processing with numeric values then we have to have all feature with numeric value or convert non-numeric values to numeric values.

## Installation

Provide instructions for setting up the project locally, including package installation:

installing libraries:
  -pandas
  -matplotlib
  -seaborn
  -RandomForestClassifier
  -KNeighborsClassifier
  -logisticRegression
  -Kflod, Cross_val_score
  -lightgbm
  -accuracy_score, f1_score, precision_score, recall_score, 
  -confusion matrix
  -xgboost
  -numpy

  ## Evaluation 
  
  It is based on comparing multiple machine learning models with their accuracy_score, f1_score, precision_score, recall_score whichever is producing best result will be considered as the optimal model or the given dataset

  ## Result

  Result of the above experiment is that it produces a good result woth KNN model 
  
