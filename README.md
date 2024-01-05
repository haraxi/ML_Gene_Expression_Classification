# Prediction of Leukemia Subtypes from Gene-Expression Data: A Machine Learning Approach

## **Course Name** 
Machine Learning for Scientists: 02-620

## **Overview**

For our Machine Learning for Scientists course project, we implemented Machine Learning models using Leukemia gene expression data. We obtained a microarray gene expression dataset for Leukemia from the Curated Microarray Database ([CuMiDa](https://sbcb.inf.ufrgs.br/cumida)). Our dataset consisted of 281 samples and 22284 genes, with 7 distinct Leukemia subtypes each represneted a different form of B-Cell Acute Lymphoid Leukemia. 

We built three classifier models and tested the performance metrics of each model. In the process we identified which subtypes are most often misclassified and which are most often correctly classified. 
Our implementations included k-Nearest Neighbours, Support Vector Machines and Logistic Regression classification models. We used a one-versus-rest approach due to the multiclass nature of our data. For our models, we built the k-NN and logistic regression models from scratch, while making use of the [scikit-learn](https://scikit-learn.org/stable/) Python module. All models were tested with 10-fold cross validation and metrics of the same were recorded as well.

## **Results**

We obtained fairly high accuracies acorss all 3 models tested. For each model, test accuracy was > 83%. We observed that from a relative standpoint, the Logistic Regression model provided the lowest accuracy, while the SVM model provided the highest accuracy. From the confusion matrices, we also found that Leukemia subytpe 4 (B-CELL_ALL_HYPO) was most misclassified as Leukemia subtype 1 (B-CELL_ALL) across all three models. This observation could be attributed to similarites in expression levels between the two subtypes, causing their misclassification with each other 

## **Collaborators**
+ Zubin Roy
+ Wrootchit Mishra
