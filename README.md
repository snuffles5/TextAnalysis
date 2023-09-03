
# Gender Classification of Hebrew Stories

This repository contains a Jupyter notebook and the results of a machine learning analysis aimed at classifying Hebrew stories based on gender.

## Contents

- `Assignment3-text-analy.ipynb`: Jupyter notebook detailing the preprocessing, modeling, and prediction steps for the Hebrew texts.
- `classification_results.csv`: CSV file containing the final predictions.

## Overview

The project employs several machine learning algorithms to classify Hebrew texts into either 'm' (male) or 'f' (female) based on their content. The analysis journey includes:

- **Preprocessing**: A significant step where Hebrew texts are tokenized and prepared for machine learning.
- **Model Selection**: A series of models including KNN, Decision Trees, Multinomial Naive Bayes, and SVM are tested and evaluated.
- **Prediction**: Using the best-performing model, predictions are made on the test set.


## Results

The predictions are saved in `classification_results.csv`. Each row corresponds to a test example, with its unique identifier and the predicted gender.
