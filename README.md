# ❤️ Heart Sound Classification using Machine Learning and Explainable AI

## Overview

This project classifies five heart sound classes using handcrafted signal-processing features and machine learning.

Classes:

- Aortic Stenosis (AS)
- Mitral Regurgitation (MR)
- Mitral Stenosis (MS)
- Mitral Valve Prolapse (MVP)
- Normal

---

## Features Extracted

- Time-domain features
- Frequency-domain features
- MFCC
- Delta MFCC
- Delta-Delta MFCC
- Chroma
- Tonnetz

Total Features: **90**

---

## Machine Learning Models

- Random Forest
- Extra Trees
- SVM
- Gradient Boosting
- Logistic Regression
- KNN
- Naive Bayes

---

## Best Results

| Model | Accuracy |
|--------|---------:|
| Random Forest | 99% |
| Extra Trees | 99% |
| SVM | 99% |

10-Fold Cross Validation

Mean Accuracy

99.9%

Standard Deviation

0.5%

---

## Explainable AI

- SHAP Summary Plot
- SHAP Feature Importance
- SHAP Interaction Analysis

---

## Visualization

- PCA
- t-SNE
- UMAP
- Confusion Matrix

---

## Tech Stack

Python

Scikit-Learn

Librosa

NumPy

SciPy

Pandas

SHAP

Matplotlib

Seaborn

---

## Results

The proposed handcrafted feature engineering combined with the Extra Trees classifier achieved:

- Test Accuracy: **99%**
- Cross Validation Accuracy: **99.9%**
- Excellent class separability in t-SNE and UMAP.
- SHAP analysis identified Spectral Entropy and MFCC features as the most influential descriptors.

