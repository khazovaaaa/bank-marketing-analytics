# Bank Marketing: Conversion Analysis and Predictive Targeting

## Overview

This project analyzes factors associated with customer conversion in bank marketing campaigns and explores how machine learning can support data-driven customer targeting.

The analysis is based on the UCI Bank Marketing dataset containing 45,211 observations.

## Objectives

- Explore customer characteristics and marketing campaign performance.
- Identify factors statistically associated with term deposit subscriptions.
- Develop and compare predictive classification models.
- Evaluate the effectiveness of model-based customer targeting.

## Methods & Tools

**Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels, Scikit-learn.

**Methods:** Exploratory Data Analysis (EDA), hypothesis testing, logistic regression, Random Forest, model evaluation, feature importance analysis, and Lift analysis.

## Key Results

- **Overall conversion rate:** 11.70%.
- **Hypothesis testing:** Statistically significant associations were identified for all five investigated factors.
- **Best-performing model:** Random Forest, with ROC-AUC of 0.7408 and Average Precision of 0.3856 on the test set.
- **Predictive targeting:** The top 10% of customers ranked by predicted probability achieved a historical conversion rate of 44.36%, compared with 11.70% overall (Lift 10% = 3.79).

## Business Implications

The results suggest that predictive modeling can help banks prioritize customers with higher estimated conversion probabilities and allocate marketing resources more effectively.

However, the findings are based on historical observational data and do not establish causal effects or guarantee similar performance in future campaigns.

## Dataset

**Source:** [UCI Machine Learning Repository — Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)

**Citation:** Moro, S., Rita, P., & Cortez, P. (2014). *Bank Marketing* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306

**License:** CC BY 4.0.

The project uses the `bank-full.csv` dataset, which is included in this repository.

## How to Run

1. Open `Bank_Marketing_Conversion_Analysis_and_Predictive_Targeting.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. The dataset is loaded directly from this GitHub repository, so no manual CSV upload is required.

## Project Notebook

[View the complete analysis](Bank_Marketing_Conversion_Analysis_and_Predictive_Targeting.ipynb)

## Project Notebook

The complete Jupyter Notebook, including data preparation, visualizations, statistical tests, machine learning models, and business recommendations, is available in this repository.
