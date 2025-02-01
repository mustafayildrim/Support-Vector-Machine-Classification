# Support Vector Machine (SVM) Classification

## Description

This project implements **binary classification** using **Support Vector Machines (SVMs)** to distinguish between two digits (**'7' and '9'**) from a dataset. Both **linear** and **nonlinear SVMs** (using a **Gaussian RBF kernel**) are trained and evaluated, with hyperparameter tuning to achieve optimal performance.

The performance of the **scikit-learn implementation** is compared with a **Projected Gradient Descent (PGD) optimizer** in terms of **classification accuracy** and **running speed**.

## Features

- **Binary classification using SVM**
- **Comparison of linear vs. nonlinear (RBF kernel) SVMs**
- **Hyperparameter tuning for optimal performance**
- **Comparison of Scikit-learn's SVM and PGD optimizer**
- **Evaluation on held-out test data**

## Technologies Used

- **Python**
- **NumPy**
- **Scikit-learn**
- **Hugging Face Datasets**

## Installation

```bash
pip install numpy scikit-learn datasets
```

## Project Tasks

### **Step 1: Load and Preprocess Data**

- Load the dataset using `datasets.load_dataset()`.
- Extract samples of digits **'7' and '9'**.
- Normalize the data if necessary.

### **Step 2: Train SVM Classifiers**

- Train a **linear SVM** classifier.
- Train a **nonlinear SVM** with an **RBF kernel**.
- Tune hyperparameters (**C** and **γ**) for better performance.

### **Step 3: Evaluate Classification Performance**

- Test both models on a **held-out test dataset**.
- Compare **accuracy and computational efficiency**.
- Report the best classification performance.

### **Step 4: Compare with PGD Optimizer**

- Train and evaluate an SVM using the **Projected Gradient Descent (PGD) optimizer**.
- Compare results against **Scikit-learn’s SVM implementation**.

## Visualizations

- **Classification Accuracy:** Compare performance of **linear vs. nonlinear SVMs**.
- **Training Time Comparison:** Evaluate running speed of **Scikit-learn SVM vs. PGD optimizer**.



