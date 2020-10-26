# Classifiers Modelselection Iris
Here i use number of models on iris dataset to check the accuracy and cross validation scores,
then accordingly i compare them which in terms helps in selecting the best classifier for our iris dataset.
# Project Overview
* Getting the dataset using url, naming the columns of the dataset.
# Performing the EDA.
### **BOXPLOT**
![](https://github.com/sarvaatmak/Classifiers_modelselection_iris/blob/main/image/box.png)
### **PAIRPLOT**
![](https://github.com/sarvaatmak/Classifiers_modelselection_iris/blob/main/image/pairplot.png)
## Splitting validation Dataset
* X_train
* X_test
* y_train
* y_test
# Building models
  **Models used are:** 
* LogisticRegression
* LinearDiscriminantAnalysis
* KNeighborsClassifier
* DecisionTreeClassifier
* GaussianNB
* Support Vector Classifier

# The Accuracy and cross validation scores are:

* ***LogisticRegression: 0.966667 (0.040825)***
* ***LinearDiscriminantAnalysis: 0.975000 (0.038188)***
* ***KNeighborsClassifier: 0.983333 (0.033333)***
* ***DecisionTreeClassifier: 0.983333 (0.033333)***
* ***GaussianNB: 0.975000 (0.053359)***
* ***Support Vector Classifier: 0.991667 (0.025000)***

# Comparing the models diagramatically.
![](https://github.com/sarvaatmak/Classifiers_modelselection_iris/blob/main/image/compare.png)

# Prediction on validation set using KNN is 0.9
