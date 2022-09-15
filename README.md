# LightGBM_with_TPE_Search

## Summary
Three main techniques were used to improve the model performance:

### 1. Target Encoding for data preprocessing

Target encoding is a simple and quick encoding method that doesn’t add to the dimensionality of the dataset.

### 2. LightGBM for model building

Faster training speed and higher efficiency
Lower memory usage
Better accuracy
Support of parallel and GPU learning
Capable of handling large-scale data
Capable of handling missing values
Capable of handling outlier
Deal imbalanced data internally
Target Encoding internally

### 3. TPE Search for hyperparameter tuning

The Tree-structured Parzen Estimator (TPE) is a sequential model-based optimization (SMBO) approach. SMBO methods sequentially construct models to approximate the performance of hyperparameters based on historical measurements, and then subsequently choose new hyperparameters to test based on this model.
