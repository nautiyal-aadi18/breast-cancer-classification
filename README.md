# Breast Cancer Classification using Machine Learning

A machine learning project that predicts whether a breast tumor is **Malignant (cancerous)** or **Benign (non-cancerous)** using the built-in Breast Cancer Wisconsin dataset from scikit-learn.

## Dataset
- 569 tumor samples, 30 numeric features (radius, texture, perimeter, area, smoothness, etc.)
- Target: 0 = Malignant, 1 = Benign (212 malignant, 357 benign)
- No missing values

## Steps in the notebook
1. Import libraries
2. Load the dataset
3. Exploratory data analysis
4. Train-test split (67% / 33%)
5. Feature scaling with StandardScaler
6. Train Naive Bayes
7. Predictions and accuracy
8. Confusion matrix
9. Classification report
10. Model comparison
11. Predicting a single tumor
12. Conclusion

## Results
| Model | Accuracy (%) | Malignant Recall (%) |
|---|---|---|
| Naive Bayes | 94.15 | 90.00 |
| Logistic Regression | 98.94 | 98.57 |
| KNN (k=5) | 96.28 | 92.86 |

Logistic Regression performed best. In medical problems, high malignant recall matters most, because missing a cancer case is costly.

## How to run
```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook cancer_classification.ipynb
```

## Note
This is an academic project. A real medical system would need far more data and testing.

## Author
Aadi Nautiyal, SRM Institute of Science and Technology
Arsh Pandey, SRM Institute of Science and Technology
