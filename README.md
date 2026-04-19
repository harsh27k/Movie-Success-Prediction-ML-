# Movie-Success-Prediction-ML-
Code repository for my research paper on predicting movie success
# Predicting Movie Success: A Comparative Analysis of Machine Learning Algorithms

This repository contains the Python codebase and dataset used for the research paper on forecasting movie success (Hits vs. Flops) using pre-release metadata.

##  Author
* **Harsh** ##
The project treats movie success prediction as a binary classification problem (IMDB Score >= 7.0 is a Hit). We compared traditional statistical models against advanced tree-based and boosting algorithms to find the most robust model for the film industry.

## 🛠️ Models Evaluated
1. Logistic Regression (Baseline)
2. Random Forest Classifier
3. CatBoost Classifier

##  Key Results
* The **Random Forest Classifier** emerged as the optimal model for this non-linear dataset.
* **Accuracy:** 86.01%
* **F1-Score:** 62.76%
* Tree-based ensembles significantly reduced the False Negative rate compared to linear models, effectively capturing outlier blockbuster hits.

## Files in this Repository
* `movie_metadata.csv`: The cleaned IMDB dataset used for training.
* `Movie_Success_Prediction.ipynb`: The Jupyter Notebook containing data preprocessing, EDA, model training, and performance evaluation metrics (Confusion Matrices & Classification Reports).
