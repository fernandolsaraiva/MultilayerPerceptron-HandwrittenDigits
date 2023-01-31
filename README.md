# MultilayerPerceptron-HandwrittenDigits

# Task 
Considerar:
* Diferentes topologias (>=5 topologias, variar número de camadas
* Usar o algoritmo original SGD (não usar algoritmos otimizados, e.g. ADAM)
* Avaliar o impacto do uso do Momentum
* Avaliar o impacto do uso da regularização (i.e. L2)
* Ilustrar graficamente a evolução do treinamento (treino/validação).

# MLP Neural Network for Classification Problem of Handwritten Digits Data Set
# 1. Introduction

In this project, we have used a data set with examples of handwritten digits. There are 1797 examples and each example has 64 pixels as inputs and 1 output (0,1,2,3,... or 9).

Our main objective was to train a Multilayer Perceptron (MLP) neural network in order to classify correctly the handwritten of a test data set.

Information about the dataset (from https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html):

* Classes: 10
* Samples per class: ~180
* Samples total: 1797
* Dimensionality: 64
* Features: integers 0-16
