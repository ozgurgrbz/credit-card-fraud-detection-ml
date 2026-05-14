# Credit Card Fraud Detection with Machine Learning

## Overview

This project applies machine learning and anomaly detection techniques to identify fraudulent credit card transactions in a highly imbalanced financial dataset. The main goal is to compare unsupervised anomaly detection methods such as Isolation Forest and One-Class SVM for detecting rare fraud cases.

The project demonstrates data preprocessing, feature scaling, anomaly detection modeling, and performance evaluation using fraud detection metrics.

---

## Dataset

The project uses the Credit Card Fraud Detection dataset available on Kaggle:

* 284,807 total transactions
* 492 fraudulent transactions
* Highly imbalanced dataset
* PCA-transformed features (V1–V28)
* Additional features include transaction time and amount

Dataset link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## Technologies Used

* Python
* pandas
* NumPy
* scikit-learn
* matplotlib
* Jupyter Notebook

---

## Machine Learning Methods

The following anomaly detection techniques are implemented:

* Isolation Forest
* One-Class SVM

The project also includes:

* Feature scaling
* Data preprocessing
* Class imbalance analysis
* Confusion matrix evaluation
* ROC-AUC analysis
* Precision-Recall analysis

---

## Project Structure

```text
credit-card-fraud-detection-ml/
│
├── fraud_detection.ipynb
├── README.md
├── requirements.txt
├── images/
└── data/
```

---

## Objectives

* Detect fraudulent transactions using anomaly detection
* Compare Isolation Forest and One-Class SVM performance
* Analyze challenges of highly imbalanced datasets
* Evaluate model effectiveness using appropriate metrics

---

## Results

The models successfully identified suspicious transactions while demonstrating the challenges of fraud detection in highly imbalanced datasets. Evaluation metrics such as ROC-AUC and Precision-Recall AUC were used to assess model performance.

---

## Future Improvements

* Hyperparameter optimization
* Deep learning approaches
* Real-time fraud detection pipelines
* Interactive dashboard visualization
* Model deployment using Streamlit or Flask

---

## Author

Ozgur Gurbuz

Master’s Student in Computer Science
Chicago State University
