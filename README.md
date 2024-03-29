# Principal Component Analysis and Car Price Prediction Using Machine Learning
The Principal Component Analysis (PCA) is a widely used method to reduce the dimensionality of large datasets while maintaining most of the relevant information. By transforming the original set of correlated variables into a smaller set of uncorrelated variables, known as principal components, PCA allows for easier analysis of complex datasets. 

In this report, we apply PCA to an automobile price prediction dataset to classify cars into three groups based on price. 

We use four different classification algorithms - logistic regression, k-nearest neighbour, decision tree, and random forest - on the original dataset and the transformed dataset (after PCA) to identify the pricing class of the cars. We then tune each model with ideal hyperparameters to improve performance and measure each algorithm’s performance using F1 score, confusion matrix, and ROC curves. We also show the decision boundaries for each model to demonstrate their fit on the dataset. 

Our analysis shows that Decision Tree Classifier outperforms the other available machine learning models. 

Finally, we conduct an experiment to interpret the model using Shapley values, an explainable AI technique, using random forest classifier model.

Overall, our algorithms successfully classify the cars into their appropriate price classes, achieving an F1 score of nearly 1.
