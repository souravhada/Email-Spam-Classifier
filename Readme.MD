# Machine Learning Classification Project

## Repository Overview

This repository contains a machine learning classification project focused on predicting spam emails using various algorithms. The project utilizes the UCI Machine Learning Repository dataset on spam emails.

## Project Overview

The main objective of this project is to build and evaluate different machine learning models to classify emails as spam or not spam. The dataset is preprocessed and split into training and testing sets. Several classification algorithms are trained and evaluated, including Logistic Regression, Naive Bayes, K-Nearest Neighbors, Support Vector Machine, Decision Tree Classifier, and Random Forest Classifier.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository. It consists of features extracted from spam and non-spam emails.

## Installation

To run this project, you need to install the `ucimlrepo` package. You can do this using pip:


## Usage

1. Open the Jupyter Notebook file `notebook.ipynb`.
2. Run the notebook cells to install necessary packages, load the dataset, preprocess the data, train various classification models, and evaluate their performance.
3. View the classification reports and confusion matrices to understand the performance of each model.
4. Explore the comparison of accuracy and false positive rates among different algorithms.

## Results

Here are the accuracy scores achieved by each algorithm:

- Logistic Regression: 91.31%
- Naive Bayes: 83.50%
- K-Nearest Neighbors: 88.71%
- Support Vector Machine: 93.16%
- Decision Tree Classifier: 79.91%
- Random Forest Classifier: 92.62%

## Comparison

The accuracy comparison among different machine learning algorithms is visualized using a line chart. Additionally, a bar graph illustrates the false positive rates (FPR) for each algorithm.

False Positive Rate (FPR) is crucial in tasks such as spam email classification because it represents the rate of non-spam emails incorrectly classified as spam. Minimizing false positives is important to prevent legitimate emails from being flagged as spam.

Considering FPR along with accuracy, we observe that Random Forest Classifier has the lowest false positive rate, indicating its ability to effectively classify spam emails while minimizing misclassification of non-spam emails. Therefore, Random Forest Classifier emerges as the best performing model for this task.

## Contributors

This project was completed by Sourav Hada. Feel free to contribute or provide feedback.
