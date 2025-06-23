# Predicting the Bioactivity of Compounds for Cystic Fibrosis

## 1. Project Objective

The goal of this project was to develop a machine learning model to accurately predict the bioactivity of chemical compounds targeting the Cystic Fibrosis Transmembrane Conductance Regulator (CFTR) protein. By creating a reliable predictive model, we can more efficiently screen large compound libraries, potentially accelerating the drug discovery process for cystic fibrosis. This was a group project for my MSc in Data Science.

## 2. Tech Stack

* **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
* **Tools:** Jupyter Notebook, Git/GitHub

## 3. Methodology

Our approach followed a systematic machine learning workflow:
1.  **Data Collection:** Extracted and processed bioactivity data from the ChEMBL public database.
2.  **Feature Engineering & Selection:** Generated key molecular descriptors from the chemical data and performed feature selection to identify the most relevant predictors. My primary responsibility was this crucial data pre-processing stage.
3.  **Modeling & Evaluation:** Trained and evaluated several supervised learning models, including Decision Tree, Random Forest, XGBoost, and Logistic Regression. I was jointly responsible for this phase.
4.  **Hyperparameter Tuning:** Optimized the best-performing models to maximize their predictive performance.

## 4. Results

After rigorous evaluation using metrics such as Precision, ROC-AUC, and F1-score, the **Random Forest model was selected as the top performer.**

* **Final F1-Score: 0.91**

This result demonstrates a robust and highly accurate method for predicting compound bioactivity.

## 5. Future Work

An individual follow-up project is planned to explore the application of Transfer Learning, using a pre-trained deep learning model to potentially achieve a new benchmark in predictive performance on this dataset.
