# Task 3: Decision Tree Classifier for Bank Marketing Outcome

As part of my Data Science Internship at **Prodigy InfoTech**, this project tackles a classic binary classification challenge: predicting if a customer will subscribe to a term deposit using features from the [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

## 📦 Dataset
- **bank.csv**: Contains client attributes and subscription outcome (`y`).

## 🔬 Task Overview

- **Goal**: Build and evaluate a Decision Tree classifier to predict `y` (term deposit subscription).
- **Features Used**: Age, job, education, marital status, default, balance, housing/loan status, contact info, recent campaign metrics, and more.

## ✨ Steps and Highlights

1. **Data Preprocessing**
   - Loaded and explored the dataset
   - Encoded categorical features numerically
   - Handled imbalanced classes
2. **Model Building**
   - Split data into train/test sets (80:20)
   - Trained a Decision Tree Classifier (`max_depth=5`, balanced weights)
3. **Evaluation**
   - Accuracy: **~79%**
   - Precision, recall, f1-score for both classes
   - Confusion matrix and tree visualization

## 🖼️ Visualizations
- Confusion matrix (model performance)
- Decision tree plot (model interpretability)

## 🚩 Key Insights

- The dataset is highly imbalanced (few positives).
- The model achieves strong precision for the majority class and good recall for identifying subscriptions.
- Business datasets like this require special handling due to class imbalance.

## 📂 Files

- **PRODIGY_DS_03.ipynb**: Complete notebook/code for this task
- **confusion_matrix.png**: Confusion matrix plot
- **decision_tree.png**: Visualization of the trained tree

## 🔗 Full Report & Code

Click to view in Colab or download locally to run:

[GitHub Repository Link here]

---

**Author:** Zeeshan Yalakpalli  
**Date:** July 22, 2025  
**Internship:** Prodigy InfoTech, Data Science

---

> *Thank you for reviewing my work! For more, connect with me on [LinkedIn](https://www.linkedin.com/).*

#ProdigyInfoTech #DataScience #MachineLearning #DecisionTree #Internship
