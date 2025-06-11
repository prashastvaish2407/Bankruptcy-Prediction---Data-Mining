# 📉 Bankruptcy Prediction – Data Mining

A data mining and machine learning project to predict corporate bankruptcy, using advanced ensemble models and feature engineering. Achieved 1st rank in class Kaggle competition.

---

## 📌 Problem Statement

Financial distress often hits with little warning. The goal: **predict bankruptcy risk** for firms using their econometric and financial data.

---

## 🎯 Objective

Develop a robust classification model that **predicts bankruptcy** accurately, ranking highly on the Kaggle leaderboard.

---

## 🗂️ Dataset Overview

- 🏢 Corporate financials and ratios
- 📊 Training and testing sets per Kaggle competition rules

---

## 🧹 Data Preprocessing

- Checked for missing values and handled outliers via **Median Absolute Deviation (MAD)**
- Normalized and standardized numerical features

---

## 🧠 Modeling Approach

- Models tried: Logistic Regression, Decision Tree, Random Forest, Gradient Boosted Trees, Neural Network, Ensemble
- Used **ensemble** of GBDT, Neural Network, and Auto Neural Net (SAS)
- Simulated cross-validation with random seeds (SAS EM limitation)

---

## 📈 Results

| Metric                  | Value    |
|-------------------------|----------|
| Validation ROC-AUC      | 91.7%    |
| Public LB ROC-AUC       | 95.2%    |
| Private LB ROC-AUC      | **98.3%**|

- **Ranked 1st** on class Kaggle private leaderboard

---

## 🧪 Libraries/Tools Used

- SAS Enterprise Miner (SAS EM)
- Python for pre/post-processing

---

## 🧠 Key Learnings

- Ensemble modeling greatly improves predictive power for rare events.
- Careful outlier handling and repeated validation are crucial.
- SAS EM’s platform constraints can be overcome with creative cross-validation approaches.

---

## 🚀 Future Work

- Implement on live financial data feeds
- Extend with survival analysis for time-to-bankruptcy predictions
- Explore explainable AI for model transparency

---

## 🤝 Acknowledgements

- [Kaggle Bankruptcy Prediction Competition](https://www.kaggle.com/competitions)
- SAS EM documentation

---

## 🏢 Example Output

> Coming soon: Bankruptcy risk probabilities for sample firms.
