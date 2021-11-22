# Fetal-Heart-Rate-using-SVM

## Problem Statement:
Fetal Heart Rate (FHR) and Uterine Contractions (UC) and it is one of the most common diagnostic 
techniques to evaluate maternal and fetal well-being during pregnancy and before delivery. 
By observing the Cardiotocography trace patterns doctors can understand the state of the fetus. 
Also, Fetal Heart Rate (FHR) monitoring remains a widely used method for detecting changes in fetal oxygenation that can occur during labor. 
By observing the Cardiotocography trace patterns doctors can understand the state of the fetus.
Therefore we will use CTG data and Support Vector Machine to predict the state of the fetus.

## Approach:
We will be using the features baseline value(verified by the medical expert), baseline value(obtained through SisPorto), accelerations, fetal movement (SisPorto), uterine contractions (SisPorto), light decelerations, severe decelerations, prolonged decelerations, repetitive decelerations to classify the fetus into three categories namely, Normal, Suspect, and Pathologic. We will use Support Vector Machine model for this purpose because of the following points:
* It scales relatively well to high dimensional data.
* SVM is not solved for local optima
* SVM models have generalization in practice, the risk of over-fitting is less in SVM.
* The kernel trick is the best thing about the SVMs

## Dataset link: http://archive.ics.uci.edu/ml/datasets/Cardiotocography

## I have published an article on the basis of this work:
Medium article link: https://medium.com/@yarasumathi/classification-of-fetal-state-using-cardiotocography-data-and-svm-b03bc8e65fd2