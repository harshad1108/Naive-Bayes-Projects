# 🚨 Cyberbullying Text Detection

## 📌 Project Overview
This project focuses on detecting **cyberbullying content** in text data using **Natural Language Processing (NLP)** and **Naive Bayes classification**.  
The goal is to automatically identify abusive or harmful language on online platforms.

---

## 🎯 Problem Statement
Given a text message or comment, predict whether it contains **cyberbullying behavior** or not.

This is useful for:
- Social media moderation
- Online community safety
- Automated content filtering

---

## 📊 Dataset
**File:** `cyber.csv`

The dataset contains text samples labeled as:
- Cyberbullying
- Non-cyberbullying

**Target Variable:**
- Cyberbullying label (1 → Yes, 0 → No)

---

## 🧠 Machine Learning Approach
- **Problem Type:** Binary Text Classification  
- **Algorithm Used:** Naive Bayes (Multinomial / Gaussian)

---

## 🛠 Techniques Applied
- Text Cleaning & Preprocessing  
- Tokenization  
- Feature Extraction (Bag of Words / TF-IDF)  
- Naive Bayes Model Training  
- Model Evaluation (Accuracy, Confusion Matrix)

---

## 🧰 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLP techniques  
- Jupyter Notebook  

---

## 📈 Results
The Naive Bayes model effectively classifies cyberbullying text, demonstrating strong performance for text-based classification tasks.

---

## 📌 Conclusion
This project demonstrates how **Naive Bayes** can be applied to **NLP-based abuse detection problems**, providing a scalable and efficient solution for real-world content moderation.

---

## 🚀 Future Improvements
- Use advanced NLP models (Word2Vec, BERT)
- Handle class imbalance
- Compare with SVM and Logistic Regression
