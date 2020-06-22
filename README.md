# Feature generation and selection methods using Ad Click data
This repository is a demonstration of some feature generation and feature selection methods using a portion of the Avazu click-through rate data from the 2015 Kaggle competition "Click-Through Rate Prediction". The dataset consists of 500000 examples, each characterized by 23 features with each example having a label of either 0 or 1 (binary classification). Only part of the dataset is provided in this repository - the full dataset can be found [here](https://www.kaggle.com/c/avazu-ctr-prediction/data). **This repository focuses on feature generation and feature selection and how these can improve the performance of a machine learning model.** The feature generation methods covered include count encoding of categorical data and creation of interaction features among an original feature set. The feature selection methods covered include L1-regularization, a univariate method that uses the f_classif scoring function, and a random forest for feature selection. The Jupyter Notebook is more tutorial-like and has lots of supplementary text whereas the .py code is just the code used in the Notebook with few comments.
