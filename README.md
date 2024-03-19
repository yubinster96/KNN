# K neareset neighbors, one of the simplest supervised machine learning algorithm
# KNN algorithm is based on FEATURE SIMILARITY: choosing the right value of k is a process called paramter tuning and is important for better accuracy
# to choose value of k: sqrt(n) where n is total number of data points
# odd value of K is selected to avoid confusion between two classes of data

#we can use knn when: data is labeled, data is noise free

The k-nearest neighbors (KNN) algorithm is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. It is one of the popular and simplest classification and regression classifiers used in machine learning today.

used diabetes csv

this data had a bunch of zeroes for certain variable inputs so we replaced it with the mean using replace

used euclidean as the metric

our confusion matrix and accuracy score tests showed us this model had low accuracy and a lot of false positive and false negatives as well
