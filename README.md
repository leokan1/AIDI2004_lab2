# Project Title

Logistic Regression and KNN ML model for Breast Cancer Wisconsin (Diagnostic) Data set

## Description

Logistic Regression and KNN ML model for Breast Cancer Wisconsin (Diagnostic) Data set

## Getting Started

### Dependencies

* requirements.txt
* Python 2.7

### Installing

```
pip install -r requirements.txt
```

### Executing program

```
python aidi2004_lab2.py
```

### Pre-trained model

* log_clf.sav for logistic regression
* knn_clf.sav for KNN
* Use pickle to load the pre-trained model
```
log_loaded_model = pickle.load(open('log_clf.sav', 'rb'))
knn_loaded_model = pickle.load(open('knn_clf.sav', 'rb'))
```

## Version History

* 0.1
* Initial Release
