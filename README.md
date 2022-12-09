# **Diabetes Classification**
Diabetes Classification with Forward Selection using Support Vector Machine Algorithm.

## Methods Used
* Machine Learning
* Data Visualization
* Supervised Learning
* Feature Selection
* Support Vectior Machine
* Forward Selection
* Model Evaluation

## Technoloqies
* Python

## Project Description
Classification is the process of predicting the class of given data points. The classification model is made using data that have a label/ target class, called supervised learning. The aim of this project is to make a classification model to classify diabetes based on the Diabetes Dataset. The feature Selection Method is used to reduce the number of input variables that could increase the complexity. 

### About Data
Dataset used in this project is **Diabetes Dataset**. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The Dataset contains 768 data with 8 features.

The dataset is sourced from Kaggle in [this link](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).

### Feature Selection Process
The Feature Selection Method used in this project is the **Wrapper Method** called **Forward Selection**. It is implemented using the help of mlxtend library. Using this method, there are 2 experiments made with different number of features. The first one use 5 number of feature and the second one use 3 number of feature.

### Classification Model
Classification Model used in this project is the **Support Vector Machine (SVM)**. The SVM algorithm creates the best decision boundary (hyperplane) with maximum margin that can separate classes.

### Conclusion
Based on the experiments conducted on a different number of features. The best precision value were obtained by the first experiment(using all of the dataset features) and the second experiment(using 5 number of features) with a precision value of 0.82. However, given the smaller number of features with the same precision result, the second experiment is better because it can eliminate irrelevant features, thereby increasing the effectiveness and work efficiency of the classification model used.
