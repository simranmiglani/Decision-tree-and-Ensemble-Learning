# Decision-tree-and-Ensemble-Learning
Classification And Regression Trees (CART for short) is a term introduced by Leo Breiman to refer to Decision Tree algorithms that can be used for classification or regression predictive modeling problems.

In this project, I will implement various ways to calculate impurity which is used to split data in constructing the decision trees and apply the Decision Tree and ensemble learning algorithms to solve two real-world problems: a classification one and a regression one.

I applied Decision Tree Classifier to classify the Iris flower data.
Next, for each value of max_depth, I trained a decision tree model and evaluated its accuracy on both train and test data, and plot both accuracies in the figure.
Next, I fine-tuned the Decision Tree Classifier using GridSearchCV.
In order to evaluate the accuracy of the prediction, I applied RandomForest, AdaBoost and Gradient Boosting.
These supervised learning models are now applied to California Housing dataset as well to predict the housing prices.
