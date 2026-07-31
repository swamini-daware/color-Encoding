# color-Encoding
This project demonstrates how to encode categorical color values(Red, Blue, Green) into numerical values using preprocessing techniquesn in Python.
# Categorical Data Encoding in Python

This repository contains a Jupyter Notebook (`Encoding.ipynb`) demonstrating common techniques for converting categorical variables into numerical values for machine learning workflows.

## 📌 Overview

Machine learning models generally require numerical inputs. This notebook demonstrates three widely used approaches to handle categorical features:

1. **Label Encoding**
   - Encodes categorical text labels into integer values (0, 1, 2, ...).
   - Implemented using `sklearn.preprocessing.LabelEncoder`.

2. **One-Hot Encoding**
   - Expands categorical columns into multiple binary columns (1s and 0s).
   - Implemented using `pandas.get_dummies()`.

3. **Target Encoding**
   - Replaces category labels with the mean of the target variable for each corresponding category.
   - Implemented using `pandas` `groupby` and `map`.

---
