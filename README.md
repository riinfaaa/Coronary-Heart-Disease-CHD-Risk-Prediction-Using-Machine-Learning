# 🫀Coronary-Heart-Disease-CHD-Risk-Prediction-Using-Machine-Learning
This project leverages supervised machine learning algorithms (primarily Decision Trees) to classify patients as high-risk or low-risk for CHD, based on anonymized clinical features.
---
## 🚀 Project Overview

Coronary heart disease (CHD) remains a leading cause of mortality worldwide. Early and accurate identification of individuals at risk is critical for proactive clinical intervention.This repository contains a complete end-to-end workflow for predicting the likelihood of coronary heart disease (CHD) using clinical and demographic data, built with Colab notebooks. 

End-to-end workflow: From importing and exploring raw data to building, evaluating, and interpreting predictive models.

Clean, robust, and reproducible: All code written for clarity and education, ideal for both practitioners and learners.

Real-world impact: Gain insights into the most predictive clinical markers for CHD.

---

## 📊 Dataset Summary
Records: 34,281 patient samples

Features: 25 total columns, including:

ID: Unique identifier

IV, A1–A22: Numeric or categorical anonymized clinical and demographic variables (e.g., exam results, age proxies)

Target: Outcome (binary: 0 = No CHD, 1 = CHD diagnosis)

---

## 🧩 Project Pipeline & Features

1. Data Exploration & Cleaning
Data loading: Import from CSV

Quick overview: .head(), .info(), .describe()

Missing value analysis & imputation

Outlier detection & handling

Balance check: Class distribution for Target

2. Data Analysis
Descriptive statistics for each feature

Correlation analysis

Visualization: Histograms, pairplots for major variables

3. Feature Engineering
Selection of informative features based on domain knowledge/correlation

Optional: Handling categorical or non-numeric entries

4. Model Building & Training
Data split: Train/test using train_test_split

Modeling: Primary—Decision Tree Classifier (scikit-learn). Adaptable for other classifiers/regressors.

Training: Fit model and obtain predictions.

5. Evaluation & Results
Metrics: Accuracy, precision, recall, F1-score, confusion matrix

Feature importance ranking: Visualize which inputs drive predictions

Prediction table: Compare ground truth vs. model output for inspection

6. Visualization
Feature distributions

Feature importance bar chart

Confusion matrix as heatmap

(Optional) Decision tree structure plots

---

## 🛠️ Tech Stack

Tool	Use

Python	Main language

Pandas	Data handling

Matplotlib	Graphing & visualization

Scikit-learn	Machine learning modeling

Google Colab	Zero setup, GPU/CPU runtime

This repository contains a complete end-to-end workflow for predicting the likelihood of coronary heart disease (CHD) using clinical and demographic data, built with Colab notebooks.

---

## 📝 How To Run

Open the notebook (coronaryheartdisease-1.ipynb) in Google Colab or Jupyter Notebook.

Upload the dataset (Project Dataset.csv) as prompted.

Run all cells step by step—follow inline comments for explanations and modify for further experimentation.

Inspect outputs: View performance metrics, visualizations, and key features for diagnosis.

---
## 🌟 Key Learnings & Insights

Practical machine learning in medicine: From messy, real-world data to deployable models.

Feature selection matters: See which medical metrics most powerfully predict risk.

Interpretable models: Decision Trees reveal how features contribute to predictions, not just raw scores.

Reusable code: Modular, commented blocks that can be adapted for other clinical prediction tasks.

