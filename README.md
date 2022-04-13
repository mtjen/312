# 312

Case Western Reserve University -> Introduction to Data Science Systems

CWRU CSDS 312 -> Spring 2022


Course project was to do something involving parallel programming. My group decided to take a large dataset of healthcare data and use cuML to increase the speed of training and testing the data with a classification model. After some simple tests of various models (decision tree, random forest, support vector machines, k-nearest neighbors, and naive bayes), we decided to move forward random forest classification as it made the most sense in terms of accuracy and possible improvement in elapsed time.

In the jupyter notebook is my code for cleaning the data, feature selection, and then using both the full dataset and the reduced dataset with the random forest classification algorithm and get accuracy score and classification reports

link to the data: https://www.cdc.gov/brfss/annual_data/annual_2020.html
