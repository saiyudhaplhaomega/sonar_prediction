# 🔍 Rock vs Mine Prediction using Machine Learning

This project predicts whether an object is a **rock** or a **mine** based on sonar signal returns, using a **Logistic Regression** classifier. It uses the [Sonar dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)) from the UCI Machine Learning Repository.

---

## 📌 Project Overview

This notebook-based project covers:
- Data collection and preprocessing
- Splitting into training and test sets
- Building and training a logistic regression model
- Evaluating model performance
- Predicting on new data

---

## 📁 Dataset

The dataset contains 208 samples with 60 features (each representing energy in a frequency band) and a label:
- **R** = Rock
- **M** = Mine

Each feature is a floating point value corresponding to sonar returns.

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy
- Pandas
- scikit-learn (LogisticRegression, train_test_split, accuracy_score)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/saiyudhaplhaomega/sonar_prediction.git
cd sonar_prediction

