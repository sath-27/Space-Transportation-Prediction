# Space-Transportation-Prediction

The aim of the work is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly.

# 1.Initially, EDA was performed to explore and understand the data. It looks at each attribute (variable) in the data to understand the nature and distribution of the attribute values. It was mainly dealt with replacing null values with measures of central tendency, dropping unwanted columns, outlier treatment and data transformation to feed into machine learning algorithms. It also examines the correlation between the variables and target variable through visual analysis. 

#2.The following step was development of a machine learning model. Many different models are tested and the performance of all models are compared through lazy classifier in which XG Boost Classifier and LGBM Classifier gave the accurate results.

#3.Later, the dataset was fed into multi-layer neural networks model considering ReLu and Sigmoid functions as activation functions. This model was around 79.5% accurate which is lesser than XGB(79.8%) but higher than LGBM(79.3%) models.


#The Dataset:
There are two input datasets namely 'test.csv' and 'train.csv' which are taken from Kaggle.
The output datasets were the predicted data with XGB,LGBM,ANN models.


