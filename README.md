# Human-Activity-Recognition

In this repository, I will show you how to develop an end-to-end machine learning pipeline for signal based time series data.
The dataset choosen for the project is from "UCI machine learning repository"
Link of the dataset is as follows:
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

An end-to-end machine learning pipeline includes the following stages.
1. Data Gathering: Collecting data and making them available for the data-scientists for further analysis
2. Data Analysis: Understanding the data and getting insights from it.
3. Feature Engineering: Transforming variables to make them ready for machine learning algorithms
4. Model building: Model building is based on bussiness value evaluation and prediction requirements.
5. Model deployment: Finally the model is deployed in the cloud which can be accessed using APIs.

In this repository I will be skipping the data gathering part, because it is already available thanks to UCI.
I will implement exploratory data analysis based on the available dataset and understand the univariate and multivariate importance of the data. Our next step will be modeing the data with most of the classical machine learning algorithms using scikit-learn library. 
After implementing all the models, I will summarise their performance with my observation using prettytable.
After implementing all the classicl machine learning models. I will proceed with some advanced machine learning techinques, which will utilize raw time series signal frames and predict state of activity out of it directly. You guessed it right, I am going to implement Neural Network for this purpose. 
I will start with implementation of LSTM on all the time series signals and observe the accuracy.
After LSTM I will implement ConvNets and observe the model performance.
Finally I will summarise importance of both classical machine learning and advanced machine learning techiniques.
