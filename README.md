# Gaussian Naive Bayes Classifier (From Scratch)

> DATA 2060 Course project – Fall 2025  
> GitHub repository: https://github.com/tongsu-brown/DATA2060_grouproject.git

## Overview

This repository contains the code and reports for a **Gaussian Naive Bayes (GNB)** classifier implemented **from scratch** in Python and compared against `scikit-learn`'s implementation.

The goal of this project is to:

- Implement the Gaussian Naive Bayes algorithm for classification without relying on ML libraries.
- Handle continuous features by modeling each feature with a class-conditional normal distribution.
- Evaluate the model on a real-world dataset and compare performance with the bulit-in sklearn.
- Provide unit tests and clear documentation so that others can reproduce and extend our work.

The repository includes:

- A clean Python implementation of GNB with evaluation (`src/project.py`).
- A final report (`report.pdf`) and presentation slides (`presentation.pdf`).

---

## Repository structure

```text
.
├── data/              
├── src/               
├── .gitignore         
├── LICENSE            
├── README.md          # This file
├── envirnment.yml            
├── presentation.pdf  
└── report.pdf         
