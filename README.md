# Nearest Earth Objects (1910-2024) Analysis

This project analyzes the NASA Nearest Earth Objects dataset to predict whether an asteroid is hazardous.

## Data Source

- **Dataset**: [NASA Nearest Earth Objects (1910-2024)](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024/data)

## Project Overview

- **Objective**: Build and evaluate models to classify asteroids as hazardous or non-hazardous.

## Data Processing

1. **Missing Values**: Filled missing values with column means.
2. **Feature Selection**: Selected features based on variance.
3. **Encoding**: Converted `is_hazardous` to binary (1 for True, 0 for False).
4. **Scaling**: Standardized feature values.

## Models

1. **Logistic Regression**
   - Accuracy: 87.1%
   - ROC-AUC Score: 0.84
   - Notes: Good overall accuracy but low recall for hazardous asteroids.

2. **Decision Tree Classifier**
   - Accuracy: 88.9%
   - ROC-AUC Score: 0.76
   - Notes: Higher recall for hazardous asteroids but slightly lower ROC-AUC score.
