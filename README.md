# Water Potability Classification with MLP

This project leverages Deep Learning to predict water potability based on physicochemical parameters, focusing on handling severe class imbalance and outliers.

## Tech Stack
- **Python 3**
- **TensorFlow / Keras** (MLP Architecture)
- **Scikit-Learn** (Preprocessing & Metrics)
- **Imbalanced-Learn** (SMOTE)

## Methodology
1. **EDA & Cleaning:** Capping outliers and Median Imputation.
2. **Preprocessing:** RobustScaler and SMOTE on the training set.
3. **Model:** MLP.

## Results
The model achieved high performance on the test set, effectively distinguishing between potable and non-potable water.

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 98% |
| **Recall** | 94% |
| **Precision** | 93% |
| **F1-Score** | 94% |

**Confusion Matrix:**

<img width="581" height="445" alt="image" src="https://github.com/user-attachments/assets/7aec5a14-9838-4b2d-b722-dfeb2727e3c2" />
