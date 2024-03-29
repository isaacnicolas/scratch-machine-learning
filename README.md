# ScratchML
## About
This repository contains implementations of some of the most popular ML algorithms from scratch. The purpose is to deepen the understanding of the concepts underlying this algorithms.

## Contents
- [About](#about)
- [Supported models](#supported-models)
- [Examples](#examples)
- [Installation](#installation)

## Supported models:
The * means that the model has implementations both for regression and classification.
### Supervised Learning:
- [Linear Regression](scratchml/supervised_learning/linear.py)
- [Logistic Regression](scratchml/supervised_learning/linear.py)
- [Decision Tree*](scratchml/supervised_learning/tree.py)
- [Random Forest*](scratchml/supervised_learning/ensemble.py)
- [Adaboost*](scratchml/supervised_learning/ensemble.py)
- [Gradient Boosting]()
- [XGBoost (eXtreme Gradient Boosting)]()
- [KNN (K Nearest Neighbors)*](scratchml/supervised_learning/clustering.py)
### Unsupervised Learning:
- [DBSCAN]()
- [K-Means]()
- [PCA (Principal component analysis)]()

## Examples
See the **examples** folder for notebooks that use the implementations.
- Linear Regression [Notebook](examples/LinearRegression.ipynb)
- Logistic Regression [Notebook](examples/LogisticRegression.ipynb)
- Decision Tree and Random Forest [Notebook](examples/DecisionTree.ipynb)
- AdaBoost [Notebook](examples/AdaBoost.ipynb)
- KNN [Notebook](examples/KNN.ipynb)  
<p align="center">
  <img src="images/KNN.png" alt="KNN visualization"/>
</p>

## Installation
```shell
git clone https://github.com/isaacnicolas/scratchml.git
cd scratchml
pip install -e .
```