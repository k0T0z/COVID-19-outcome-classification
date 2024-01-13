# COVID 19 Outcome Classifier
This is my analysis of different classifiers on WHO organization's dataset using scikit-learn.

# KNeighborsClassifier, LogisticRegression, and GaussianNB: [COVID19_outcome_classifier.ipynb](https://nbviewer.org/github/k0T0z/COVID-19-outcome-classifier/blob/master/COVID19_outcome_classifier.ipynb)
# DecisionTreeClassifier and SVC: [COVID19_outcome_classifier2.ipynb](https://nbviewer.org/github/k0T0z/COVID-19-outcome-classifier/blob/master/COVID19_outcome_classifier2.ipynb)

# View the notebook using nbviewer from here: 

# Best hyperparameters for each model

## K-Nearest Neighbors (KNN)

| Parameter | value |
| --- | --- |
| n_neighbors | 3 |
| weights | uniform |
| algorithm | auto |
| leaf_size | 10 |
| p | 2 |
| metric | minkowski |
| metric_params | None |
| n_jobs | None |

## Logistic Regression (LR)

| Parameter | value |
| --- | --- |
| penalty | l2 |
| dual | False |
| tol | 0.0001 |
| C | 112.9 |
| fit_intercept | True |
| intercept_scaling | 1 |
| class_weight | None |
| random_state | 42 |
| solver | lbfgs |
| max_iter | 100 |
| multi_class | auto |
| verbose | 0 |
| warm_start | False |
| n_jobs | None |
| l1_ratio | None |

## Naïve Bayes (NB)

| Parameter | value |
| --- | --- |
| priors | None |
| var_smoothing | 1000.0 |

## Decision Trees (DT)

| --- |
| --- |

## Support Vector Machines (SVM)

| --- |
| --- |

# Each model's performance

| --- | Precision | Recall | f1 | Cross Validation | ROC | AUC |
| --- | --- | --- | --- | --- | --- | --- |
| K-Nearest Neighbors (KNN) | 0.96 | 0.96 | 0.96 | 0.7069 | --- | 0.90 |
| Logistic Regression (LR) | 1.00 | 0.95 | 0.97 | 0.7055 | --- | 0.93 |
| Naïve Bayes (NB) | 1.00 | 0.86 | 0.92 | 0.9375 | --- | 0.88 |
| Decision Trees (DT) | --- | --- | --- | --- | --- | --- |
| Support Vector Machines (SVM) | --- | --- | --- | --- | --- | --- |

# Conclusion


# References

1. [Understanding The Confusion Matrix From Scikit Learn](https://towardsdatascience.com/understanding-the-confusion-matrix-from-scikit-learn-c51d88929c79)

