# Iris-Flower-Classification
This project is a comprehensive application of Machine Learning techniques using Python programming, specifically leveraging the Scikit-learn (sklearn) library. The objective is to classify Iris flowers into one of three species: Setosa, Versicolor, or Virginica based on the measurements of their petal and sepal dimensions.

The Iris dataset is a well-known and widely used dataset in pattern recognition and machine learning, consisting of 150 samples with 4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width

This project demonstrates the application of both supervised and unsupervised machine learning algorithms. However, the core focus is on supervised learning, where the model is trained on labeled data.

Algorithms Used
1. Decision Tree Classifier
A tree-like model used for classification tasks.

It splits the dataset into subsets based on feature values, creating a model that is easy to interpret.

Pros: Easy to visualize, handles non-linear relationships well.

2. K-Nearest Neighbors (KNN)
An instance-based learning algorithm that classifies new data based on the majority label of its k nearest neighbors in the training set.

It works well with small datasets like Iris and is non-parametric.

3. Support Vector Machine (SVM)
A powerful classifier that finds the optimal hyperplane which maximizes the margin between different classes.

Works well for both linear and non-linear classification using kernel tricks.

4. Logistic Regression
A statistical model that uses a logistic function to model the probability of a binary or multi-class outcome.

Useful for predicting probabilities and interpreting the influence of features.

Evaluation Metrics Used
To measure the effectiveness of each model, several performance metrics were used:

Accuracy Score: Percentage of correct predictions out of the total samples.

Confusion Matrix: A matrix to visualize true positives, true negatives, false positives, and false negatives.

Classification Report: Includes metrics like:

Precision – proportion of correct positive predictions.

Recall – proportion of actual positives correctly identified.

F1-Score – harmonic mean of precision and recall.

Additionally, for some models, cross-validation was applied to ensure the model’s generalization on unseen data.

Conclusion
This project not only helps in understanding different supervised machine learning algorithms but also highlights the power of Python’s data science libraries like pandas, matplotlib, seaborn, and scikit-learn. The visualizations and accuracy comparisons among models provide a strong foundation for beginners to learn classification techniques using real-world datasets.
