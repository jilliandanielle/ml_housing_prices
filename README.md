# ml_housing_prices

For this project, I am imitating a data scientist recently hired at a real estate company

1. Look at the big picture. 
2. Get the data. 
3. Discover and visualize the data to gain insights. 
4. Prepare the data for Machine Learning algorithms. 
5. Select a model and train it. 
6. Fine-tune your model. 
7. Present your solution. 
8. Launch, monitor, and maintain your system.

## Tools used
Pandas, NumPy, Scikit-learn, Seaborn, TensorFlow, Jupyter Notebook

### Discover and visualize the data to gain insights
Scatterplots, heat maps, scatter_matrix to plot every numerical attribute against every other numerical attribute, creating functions for data cleaning to account for missing data. Scikit-Learn's class SimpleImputer to take care of missing values. Scikit-Learn's OrdinalEncoder class to convert text to numbers. 
 
 
 ### Training the model
 Linear Regression Model from sklearn
 
 DecisionTreeRegressor from sklearn
 
 Cross-Validation - using the train_test_split function to split the training set into a smaller training set and validation set then train the models against the smaller training set and evaluate them against the validation set. 
 
 RandomForestRegressor from sklearn - works by training many Decision Trees on random subsets of the features, then averaging out the predictions. 