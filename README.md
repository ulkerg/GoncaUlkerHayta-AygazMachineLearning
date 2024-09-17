# GoncaUlkerHayta-AygazMachineLearning

Since I am interested in data analytics, I chose the Churn Prediction problem.

Machine Learning Algorithms for Churn Prediction

https://www.kaggle.com/code/goncalkerhayta/notebookcc0225f70d/edit/run/196994669

Supervised
*****Decision Tree*****
              precision    recall  f1-score   support

           0       0.99      0.99      0.99     30419
           1       0.94      0.93      0.93      4273

    accuracy                           0.98     34692
   macro avg       0.96      0.96      0.96     34692
weighted avg       0.98      0.98      0.98     34692

*****Decision Tree*****Trained
              precision    recall  f1-score   support

           0       0.99      1.00      1.00     30419
           1       0.98      0.96      0.97      4273

    accuracy                           0.99     34692
   macro avg       0.99      0.98      0.98     34692
weighted avg       0.99      0.99      0.99     34692

#The model performs exceptionally well in predicting non-churners (Class 0) with a precision and recall of 0.99, 
while also achieving strong results for churners (Class 1) with a precision of 0.94 and recall of 0.93. 
Overall, the model maintains a high accuracy of 0.98, demonstrating robust performance even with the class imbalance.

#Increased Recall value with trained model. For churn prediction, we can say that the Decision Tree algorithm works quite well.

Unsupervised
K-Means

Silhouette Score: 0.42231604790285676

#In a churn prediction problem, we cannot directly use unsupervised learning algorithms. In such problems, we can perform clustering to identify customer segments with a high likelihood of churn. After clustering, it would be more appropriate to continue with supervised algorithms.

#In this project, I aimed to select the right features and the optimal number of clusters to achieve a high Silhouette Score. Looking at the Silhouette Score, we can say that the clustering is bad.
