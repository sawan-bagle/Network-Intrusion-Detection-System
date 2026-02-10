Network Intrusion Detection System using NSL-KDD
Overview

This repository contains an implementation of a multi-class Network Intrusion Detection System (NIDS) using the NSL-KDD dataset.
The system classifies network traffic into normal activity or specific categories of cyber attacks using machine learning techniques.

Unlike traditional binary intrusion detection systems, this project focuses on attack-type classification, which provides deeper insight into network threats.

Dataset

Dataset: NSL-KDD

Purpose: Improved version of KDD’99 with reduced redundancy and better class distribution

Attack Classes

All attack records are grouped into the following categories:

Normal

Denial of Service (DoS)

Probe

Remote to Local (R2L)

User to Root (U2R)

Approach
Data Preprocessing

Handling categorical and numerical features

Label encoding of attack types

Feature selection and normalization

Train–test split for evaluation

Model

Random Forest Classifier

Suitable for high-dimensional network data

Robust against overfitting

Provides feature importance for interpretability

Evaluation

The model is evaluated using:

Confusion Matrix

Precision, Recall, and F1-score

Multi-class ROC-AUC

Feature importance analysis

The results demonstrate reliable detection across multiple attack categories with balanced performance.

Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

How to Run

1.Clone the repository:

git clone https://github.com/your-username/nids-nsl-kdd.git


2.Open the notebook:

jupyter notebook NIDS(NSL_KDD).ipynb


3.Run the notebook cells sequentially.
