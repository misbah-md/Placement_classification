# Student Placement Classification

A machine learning project that predicts student placement outcomes based on academic performance, skills, and other relevant factors.

## 📊 Project Overview

This project analyzes student data to build a classification model that predicts whether a student will get placed or not. The model uses various features including academic performance, internship experience, communication skills, and more to make accurate predictions.

## 🚀 Features

- **Data Preprocessing**: Handles categorical variables and class imbalance
- **Multiple Algorithms**: Implements various classification algorithms
- **Performance Metrics**: Comprehensive evaluation with confusion matrix and classification reports
- **Visualization**: Clear data visualization and model performance charts
- **Undersampling**: Addresses class imbalance using RandomUnderSampler

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble%20Learning-green?logo=xgboost&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-blue?logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![imbalanced-learn](https://img.shields.io/badge/imbalanced--learn-Data%20Sampling-lightgrey)

## 📁 Dataset

The dataset contains the following features:

- **College_ID**: Unique identifier for each student
- **IQ**: Intelligence quotient score
- **Prev_Sem_Result**: Previous semester academic performance
- **CGPA**: Cumulative Grade Point Average
- **Academic_Performance**: Overall academic performance score
- **Internship_Experience**: Whether the student has internship experience
- **Extra_Curricular_Score**: Participation in extracurricular activities
- **Communication_Skills**: Assessment of communication abilities
- **Projects_Completed**: Number of projects completed
- **Placement**: Target variable (Yes/No)


## 🎯 Model Performance
- The XGBoost classifier achieves excellent performance:

- Accuracy: 100%

- Precision: 100% for both classes

- Recall: 100% for both classes

- F1-Score: 100% for both classes

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
[![License:MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

<div align="center">
⭐ Don't forget to star this repository if you find it helpful!
</div> 

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/sriniketh-bobbili/student-placement-classification.git
cd student-placement-classification
