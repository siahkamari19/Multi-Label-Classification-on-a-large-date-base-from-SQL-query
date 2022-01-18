# **MultiClass Classification on 311 New York complaint calls**
 
In this project I have designed a MultiClass classification task on the data with various algorithms along with data visualization to better understand the data and coloration between the features and the classes.
 
The algorithms used for this project are as follows:
 
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K Nearest Neighbors
5. Support Vector Classifier
6. Ada Boost
7. Gradient Boost
8. Extreme Gradient Boost
9. Naive Bayes
10. Neural Network
 
The features and the amount of data have been selected based on computation power limitation, intuition, trial/error on all the algorithms above, the best features to classify 60 classes from most common complaints which have been randomly selected from all of the dataset to sample 25000 data points are as follow:
 
1. incident_zip
2. location_type
3. created_date
4. agency
5. latitude
6. longitude
7. descriptor
 
The Neural Network Sequential model has been tuned manually on all the scenarios since I couldn't run grid search for fine tuning the hyperparameters.
 
With the amount of data that I have I could run the algorithm only once after OneHotEncoding the data for NN Model.
