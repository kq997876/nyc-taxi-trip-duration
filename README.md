# nyc-taxi-trip-duration

The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this playground. Based on individual trip attributes, should predict the duration of each trip.

The notebook includes data processing, EDA, Feature Engineering and Modeling parts. Data Analysis has been done followed by modeling as follows:

XGBoost RMSLE: 0.0695
LinearRegression RMSLE: 0.1097

DecisionTree RMSLE: 0.0838

RandomForest RMSLE: 0.0821
