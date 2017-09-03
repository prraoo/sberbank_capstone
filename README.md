# Sberbank Capstone Project

## Overview:
This project is based on the Kaggle competition: “[Sberbank Russian Housing Market](https://www.kaggle.com/c/sberbank-russian-housing-market)”. This project is developed as a part of Capstone Project for Udacity Machine Learning NanoDegree program. The project aims to present a general structure for tackling real-world machine learning problems using powerful algorithms such as XGBoost and Multi-Layer Perceptron.

This project is divided into different notebooks, a brief rundown of the various sections is given below:
- **Part 0** [Sberbank_Exploratory_Data_Analysis](https://github.com/raoanonymous/sberbank_capstone/blob/master/Sberbank_Exploratory_Data_Analysis.ipynb): Exploration of the raw dataset, identify anomalies/ outliers, create visualizations of different features.  
- **Part 1** [Data Cleaning](https://github.com/raoanonymous/sberbank_capstone/blob/master/Data_Clean.ipynb) and [Feature Engineering](https://github.com/raoanonymous/sberbank_capstone/blob/master/FeatureEngg.ipynb) : The handling of outliers, feature engineering based on timestamp and validation on train-test data
- **Part 2** [XGBoost Model and Tuning](https://github.com/raoanonymous/sberbank_capstone/blob/master/XGBoost.ipynb): Using the famous XGBoost library, regression model is developed by tuning important hyper-parameters
- **Part3** [MLP Model](https://github.com/raoanonymous/sberbank_capstone/blob/master/NN_Model.ipynb): Using Keras with TensorFlow library in the backend, neural network model is built. The model is check for overfitting and also using sklearn GridSearch method, hyper-parameters are tuned to get the optimal model.
- **Part 4** [Stacking and Validation](https://github.com/raoanonymous/sberbank_capstone/blob/master/FinalStacking.ipynb): In this last section, the predictions from the base models are combined using Linear Regression Model and also the model is validated for its robustness.

The entire project implemetation, methodology and results are summarized in [Capstone Report](https://github.com/raoanonymous/sberbank_capstone/blob/master/report.pdf) without delving deep into the project.

## Requirements: 

### Dataset

The dataset used in the project can be downloaded from the competition [data](https://www.kaggle.com/c/sberbank-russian-housing-market/data) section by agreeing to the rules of the competitions.

### Software 
In order to run the project, Python 3.5 (preferably using Anaconda platform) is necessary along with the follwing packages:

- Python stack: python 3.5.3 numpy, scipy, sklearn, pandas, matplotlib.
- XGBoost: multi-threaded xgboost should be compiled, xgboost python package is also required.
- Deep Learning stack: CUDA 8.0.61, cuDNN v6, tensorflow-gpu 1.2.1 (compiled with GPU flags), Keras. 

The exact version of the packages and the environment used for the project can be found in [project environment](https://github.com/raoanonymous/sberbank_capstone/tree/master/environment).

## Acknowlegements

I would like to acknowledge following community/ people without whom this project would have been not possible:

- Sberbank for share the precious real-estate datasets.
- Kaggle Community for hosting the competition and sharing ideas.
- [dnkirill](https://github.com/dnkirill) for sharing a structural approach to solve ML problems for beginners.
- Finally, Udacity for giving opportunity for the students to implement a project of choice.





