
Traditional machine learning model development is resource-intensive, requiring significant domain/statistical knowledge and time to produce and compare dozens of models. 
With automated machine learning, the time it takes to get production-ready ML models with great ease and efficiency highly accelerates. However, the Automated Machine Learning does not yet provide much in terms of data preparation and feature engineering. 
The AutoBrewML tries to solve this problem at scale as well as simplifies the overall process for the user. It leverages the Automated ML coupled with components like Data Profiler, Data Sampler, Data Cleanser, Anomaly Detector which ensures quality data as a critical pre-step for building the ML model. 
With AutoBrewML the time it takes to get production-ready ML models with great ease and efficiency highly accelerates


Modules
-----------
- **Acquisition_DataTypeConversion** : Data Acquisition & Transformation 
- **BrewDataProfiler** : Exploratory Data Analysis
- **BrewDataSampling** : Data Sampling
 
  - Random Sampling
  - Stratified Sampling
  - Systematic Sampling
  - Cluster OverSampling (with SMOTE)
- **BrewDataCleanser** : Data Cleansing
- **BrewAnomalyDetection** : Anomaly Detection
- **BrewTrainTestSplit** : Train-Test Split the data in a given ratio
- **BrewFeatureSelection** : Selection of Most Important Features before Modelling
- **BrewAutoML_Classifier** : Auto trigger and choose ML Model for Classification
- **BrewAutoML_Regressor** : Auto trigger and choose ML Model for Regression
- **BrewAutoML_TimeSeries** : Auto trigger and choose ML Model for Time series Forecasting
- **Responsible AI Guidelines** 
 
  - **BrewFairnessEvaluator** : Evaluate the Fairness of a Model with respect to metrics across various cohorts of a sensitive feature
  - **BrewDisparityMitigation** : Mitigate the Bias observed in above Evaluator



**Prerequisites:**
- Python version >=3.8.0