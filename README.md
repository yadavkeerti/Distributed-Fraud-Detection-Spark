# 🚀 Distributed Credit Card Fraud Detection using Apache Spark

## 📌 Project Overview

This project demonstrates how **Apache Spark** can be used for **distributed data processing** to detect fraudulent credit card transactions using machine learning.

With the rapid growth of digital payments, detecting fraud in real-time is a critical challenge. This project leverages **big data processing + AI** to build an efficient fraud detection system.

---

## ⚙️ Technologies Used

* 🐍 Python
* ⚡ Apache Spark (PySpark)
* 🤖 Machine Learning (Logistic Regression, Random Forest)
* 📊 Matplotlib & Seaborn

---

## 📊 Dataset

* Source: Kaggle (Credit Card Fraud Detection Dataset)
* Total Transactions: **284,807**
* Features: **31**
* Target Variable: `Class`

  * 0 → Normal
  * 1 → Fraud

⚠️ The dataset is **highly imbalanced**, making fraud detection challenging.

---

## 🧠 Key Concepts Used

* Distributed Data Processing using Apache Spark
* Data Preprocessing and Feature Engineering
* Handling Imbalanced Data
* Machine Learning Model Training
* Model Evaluation using Confusion Matrix and Metrics

---

## 🏗️ Project Workflow

1. Load dataset using Spark DataFrames
2. Analyze and understand data distribution
3. Handle class imbalance using sampling
4. Convert features using VectorAssembler
5. Train ML models (Logistic Regression, Random Forest)
6. Evaluate model using:

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * Confusion Matrix

---

## 📈 Results

* High accuracy in detecting normal transactions
* Effective fraud detection with low false positives
* Visual analysis using graphs and confusion matrix

---

## 🌐 Distributed Computing Aspect

Apache Spark processes data in a **distributed manner** by:

* Splitting data into partitions
* Processing them in parallel
* Enabling scalable and efficient computation

---

## 🎯 Conclusion

This project shows how **Apache Spark + Machine Learning** can be combined to solve real-world problems like fraud detection.
It highlights the importance of distributed systems in handling large-scale data efficiently.

---

## 🙌 Author

**Keerti Yadav**
