# Diabetes Prediction Uisng Machine Learning Algorithm
# Overview

To create a Model which can be used to Predict Diabetes.

# Motivation

I was also very inquisitive in Medical Science since childhood. Data science is such a great field that can be implemented in many domains therefore it allowed me to explore and do a project in the health care domain. I wanted to do something for my grandmother as she has gone through a lot because of diabetes hence I decided to find out how can I use Machine Learning for prediction.

# Introduction
Diabetes is a chronic disease that occurs if the pancreas does not create enough insulin or if insulin is utilized ineffectively. A hormone called insulin that helps to control the amount of blood sugar. Controversial diabetes leads to hyperglycemia or high blood sugar, causing severe damage over time to numerous bodily systems, including the brain and blood arteries. 
The risk factor and seriousness of diabetes may be significantly reduced when accurate early predictions are possible. Although there is little biological data study, technological advances have enabled the use of computational and statistical analytic methods. Healthcare organizations are also gathering a substantial amount of data. New information becomes available when data mining methods are applied to build models that learn from observable data. Data mining is the process of data extraction and may be utilized to create a more effective medical decision-making process. For illness prediction and knowledge discovery from biomedical data, a variety of data mining approaches have been used.

# Project contribution

- Provide the features for diabetes prediction.
- Provide the Pearson correlation for feature selection for extracting the most important features.
- To estimate total diabetes assessment metrics using machine-learning techniques such as K-Nearest Neighbor, Random Forest, and Vector Machine support.
- Comparing the above machine learning algorithms by hyper tuning the parameters yield the best accuracy for diabetes prediction

# Dataset

The data set was acquired from the Diabetes and Digestive and Renewable Diseases National Institute (NIDDK). The objective of the dataset is to diagnose a patient with diabetes using diagnostic measures in the dataset. There were many limitations to the selection of these cases from a wider database. Pima Indian women are all patients in this clinic who are at least 21. The data consist of 768 rows * 9 columns

## Data Preprocessing
 For the cleaning and preparation of data for a machine learning model that increases model accuracy and efficiency, preprocessing data is required. The following steps are:
o	Getting the dataset: diabetes.csv
o	Importing libraries: Numpy, Pandas
o	Importing datasets
o	Finding Missing Values
o	Encoding Categorical Data
o	Splitting dataset into training and test set
o	Feature scaling

## Feature Selection
 From the Pearson Correlation matrix, it is been observed that the feature name “Pregnancies” has a higher correlation when compared to other features. So this column is removed from the final dataset before training the model.

## 	Algorithm Implementation
### K Nearest Neighbor (K-NN)
Based on the supervised learning technology, the K-Nearest Neighbor algorithm is one of the most fundamental machine teaching algorithms. The maximum accuracy has been achieved through the K-Nearest Neighbor algorithm is by using hyper tuning the parameter as Distance (Distance = Euclidean) is 0.74. 

###  Random Forest Classifier
Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It builds decision trees on different samples and takes their majority vote for classification and average in case of regression. The maximum accuracy has been achieved through the Random Forest algorithm is by using hyper tuning the parameter as Maximum Number of Trees as 500 and Maximum Depth as 3 is 0.82.

### Support Vector Machine
The SVM technique thus helps to identify the optimum line or decision limit, also known as a hyper-plane. The data points or vectors closest to the hyperplane and influencing the position of the hyperplane are known as support vectors. These vectors are called vectors supporting the hyperplane. The difference between the hyperplanes and the vectors is termed the margin. SVM's objective is to boost this margin as much as feasible. The hyperplane with the largest margin is the best. The maximum accuracy has been achieved through the Support Vector Machine is by using the parameter as Polygon is 0.81.

- The assessment measures for accuracy, F1 Score, precision, the recall was carried out by evaluating the machine-learning algorithms, i.e., K-Nearest Neighbor, Random Forest Classifier, and Support Vector Machine.

# Conclusion

The result has been inferred that the Random Forest algorithm hyper tuned with the Maximum number of trees as 100 and Maximum depth as 2 gives an accuracy of 0.82 and the nearer accuracy has been achieved using the Support Vector Machine algorithm by hyper tuning the parameter Kernel as poly which is 0.81. Hence both the algorithm gives similar accuracy and thus both the algorithms can be used for prediction for diabetes which predicts whether or not a patient has diabetes effectively. For the future, a large amount of data can be trained with various hyper tuning parameters in order to increase the efficiency and the best accuracy can use widely in diabetes prediction.


