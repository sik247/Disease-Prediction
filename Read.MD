#Disease Prediction using Machine Learning

This repository contains Python code for disease prediction using machine learning. The code is designed to predict disease outcomes based on a given dataset.

#Data Source
The dataset used for this project is sourced from Kaggle and consists of two CSV files: Training.csv and Testing.csv. The data is read from the Testing.csv file, and any columns with missing values are removed.

#Data Exploration
Exploratory data analysis is performed to gain insights into the dataset. The balance of the dataset in terms of disease distribution is visualized using bar charts to understand the distribution of diseases.

#Data Preprocessing
The target values, representing disease labels, are encoded into numerical values using label encoding. This step is essential for preparing the data for machine learning algorithms, as many models require numerical input.

#Data Splitting
The dataset is split into training and testing sets. In this specific project, an 80-20 split ratio is used, with 80% of the data used for training and 20% for testing.

#Machine Learning Models
Three machine learning models are used for disease prediction:

Support Vector Classifier (SVC)
Gaussian Naive Bayes Classifier
Random Forest Classifier
K-Fold Cross Validation
K-Fold cross-validation is employed to evaluate the performance of the machine learning models. The dataset is divided into K subsets, and each model is trained and tested K times, with a different subset used as the test set in each iteration. This helps assess the models' generalization performance.

#Scoring Metric
The scoring metric for cross-validation is accuracy. Accuracy measures the proportion of correctly predicted disease outcomes compared to the total number of samples.

#Results
The code provides cross-validation scores and mean scores for each machine learning model. The results can be used to assess the models' performance and choose the most suitable model for disease prediction.

#Conclusion
This project demonstrates the application of machine learning techniques to predict disease outcomes based on a given dataset. The code can be customized and extended for different datasets and healthcare applications.

Please note that the dataset used in this project is illustrative, and real-world disease prediction tasks may require larger and more diverse datasets for accurate results.
