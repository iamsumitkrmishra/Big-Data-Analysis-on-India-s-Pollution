# Big Data Analytics Project: India Air Quality Analysis

### 91262 - DATA MINING, TEXT MINING AND BIG DATA ANALYTICS

### 91284 - PROJECT WORK IN DATA MINING, TEXT MINING AND BIG DATA ANALYTICS	

### SUMIT KUMAR MISHRA_0001055762 

## Project Overview
Continuous hourly air quality data is collected from major Indian cities — Mumbai, Delhi, Kolkata, and Chennai — including indicators such as pollutant concentrations and temperature.

In this project, we perform the following analysis:
1. Read and clean the datasets for all four cities
2. Analysis of missing values and outliers
3. Add a unified time series column and analyze temperature and pollutant trends grouped by time
4. Cluster analysis on the pollutant PM2.5
    * KMeans
    * BisectingKMeans
    * ClusterEvaluator
5. Based on all city data, train a classifier model with the city name as the label
    * StringIndexer
    * VectorAssembler
    * StandardScaler
    * DecisionTreeClassifier
    * RandomForestClassifier
    * MulticlassClassificationEvaluator

## Mini-Project
6. Calculation of the Air Quality Index (AQI) based on pollutant concentration data
    * UDF
7. Regression algorithm prediction of AQI
    * LinearRegression
    * DecisionTreeRegressor
    * RandomForestRegressor
    * RegressionEvaluator
8. Classification of air quality levels based on the AQI
9. Apply classifier algorithms to predict air quality category
    * NaiveBayes
    * MultilayerPerceptronClassifier
    * DecisionTreeClassifier
    * RandomForestClassifier
    * LogisticRegression

