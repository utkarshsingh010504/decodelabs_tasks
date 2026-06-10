# Iris Species Classification using K-Nearest Neighbors (KNN)

This project demonstrates a simple end-to-end Machine Learning workflow to clean a dataset, preprocess features, and build a predictive model using the K-Nearest Neighbors (KNN) algorithm. Based on the target variable `species` and the dataset dimensions, this model is configured for the classic Iris flower classification problem.

---

## 🚀 Project Overview

The goal of this project is to predict the species of a flower based on its structural characteristics. The workflow includes:
1. **Data Cleaning:** Removing duplicate entries and handling missing values to ensure high data quality.
2. **Feature Engineering:** Separating independent features ($X$) from the target label ($y$).
3. **Model Training:** Splitting the data into training and testing sets, then fitting a KNN classifier.
4. **Evaluation:** Scoring the model's predictive accuracy on unseen test data.

---

## 📊 Dataset Details

* **Target Variable:** `species`
* **Cleaned Data Shape:** 149 rows, 5 columns (after dropping duplicate records)

---

## 🛠️ Prerequisites & Installation

To run this notebook, you need Python installed along with the following libraries:

```bash
pip install pandas scikit-learn
