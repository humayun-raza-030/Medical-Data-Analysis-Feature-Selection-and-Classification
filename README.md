# Medical Data Analysis: Feature Selection & Classification

## Overview
This project explores **feature selection and classification techniques** on two **medical datasets**: **Cancer** and **Diabetes**. It applies **machine learning models** to classify diseases and utilizes **Principal Component Analysis (PCA)** for dimensionality reduction.

## Datasets
- **Cancer Dataset**: Contains medical attributes related to cancer diagnosis.
- **Diabetes Dataset**: Features various health indicators used to detect diabetes.

Each dataset is processed separately, and the results are compared independently.

## Tasks Performed

### **Task 1: Data Preprocessing & Model Implementation**
- **Performed data preprocessing**, including:
  - Handling missing values.
  - Normalizing features where necessary.
  - Splitting the dataset into training (80%) and testing (20%) sets.
- **Implemented the following machine learning models** with at least three different parameter settings:
  - **Decision Tree**
  - **Random Forest**
  - **Naïve Bayes**

### **Task 2: Principal Component Analysis (PCA) & Model Optimization**
- **Applied PCA with a correlation matrix** and reported findings.
- **Ran PCA for different variance thresholds** to determine optimal dimensionality reduction.
- **Selected the most important attributes** based on PCA results and justified their importance.
- **Re-implemented Decision Tree, Random Forest, and Naïve Bayes** using the refined feature set.

## Performance Comparison
- Evaluated model performance based on:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**
- Compared results **before and after PCA** to assess the impact of dimensionality reduction.

## Results
- The best-performing algorithm for the **Cancer dataset** was **(Insert Best Algorithm Here)**, achieving **(Insert Accuracy Here)** accuracy.
- The best-performing algorithm for the **Diabetes dataset** was **(Insert Best Algorithm Here)**, achieving **(Insert Accuracy Here)** accuracy.
- PCA helped improve/reduce model performance by **(Insert Impact Here)**.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/medical-data-analysis.git
