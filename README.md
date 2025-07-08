# 💳 Credit Card Fraud Detection

This project was developed as part of the **CodeClause Internship**.  
It aims to detect fraudulent credit card transactions using machine learning techniques on an imbalanced dataset.

---

## 🎯 Aim

To detect fraudulent transactions in a credit card dataset using classification models and data balancing techniques.

---

## 📄 Description

The dataset contains anonymized credit card transactions made by European cardholders in September 2013.  
The key challenge is that fraudulent transactions are very rare compared to genuine ones.

To tackle this, the project includes:
- Handling imbalanced data using under-sampling
- Applying Logistic Regression for binary classification
- Evaluating the model using accuracy, precision, recall, and ROC-AUC

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📁 Dataset Source

[🔗 Kaggle: Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🔍 What I Learned

- How to handle highly imbalanced datasets
- Binary classification using Logistic Regression
- How to evaluate models using various performance metrics
- Data visualization and preprocessing

---

## 🧠 Model Performance (Sample Output)

| Metric        | Value     |
|---------------|-----------|
| Accuracy      | 94%+      |
| Precision     | ~95%      |
| Recall        | ~93%      |
| ROC AUC Score | 0.96+     |

---

## 📽️ Video Explanation

[🔗 Add Your YouTube/Drive Link Here]
🔹 Confusion Matrix:
[[ 86   1]
 [ 10 100]]

🔹 Classification Report:
              precision    recall  f1-score   support

           0       0.90      0.99      0.94        87
           1       0.99      0.91      0.95       110

    accuracy                           0.94       197
   macro avg       0.94      0.95      0.94       197
weighted avg       0.95      0.94      0.94       197

🔹 Accuracy Score: 0.9441624365482234
🔹 ROC AUC Score: 0.9487983281086729

---

## 📌 Project Structure

