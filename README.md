# a4-starter
 In this assignment I have used multiple regression algorithms to predict dengue cases. As a brief summary of my work, I've done the following steps
 
1.  Load data and fill missing values using ffill
2. Add 'mean vegetation index' as a feature, and added lagged versions of the top 3 features (dew point, humidity etc.)
3. Select top 7 features using RFE with RandomForestRegressor
4. Split data into train/test
5. Implemented KNN, RidgeCV, Random Forest, Gradient Boosting, and Bagging Regressors.
6. Compare the performances by looking at visualizations.
7. Save the best performing file to submit
