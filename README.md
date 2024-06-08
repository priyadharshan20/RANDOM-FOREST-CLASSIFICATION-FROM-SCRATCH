# RANDOM-FOREST-CLASSIFICATION-FROM-SCRATCH

**Introduction**
- We have developed a Random Forest model from scratch to predict heart failure outcomes using the heart failure clinical records dataset. This implementation does not rely on any machine learning libraries or frameworks, allowing a deeper understanding of the underlying algorithms.

**Prerequisites**

- python
- pandas and numpy
- Knowledge on Decision Tree 
- Knowledge on Random Forest

**Dataset**
- The dataset consists of clinical records related to heart failure. It includes various features such as age, ejection fraction, serum creatinine, and more. The target variable is DEATH_EVENT, indicating whether a patient experienced a fatal heart failure event.

**The project is divided into several key components:**

**Data Handling:**

- The dataset is loaded and split into training and testing sets (80% training, 20% testing).
  
**Tree Data Structure:**

- A Tree class is defined to represent the nodes of the decision tree, with attributes for the splitting feature, threshold, child nodes, and value at the leaf.

**Splitting Functions:**

- Functions to split the dataset based on a given feature and threshold, creating left and right subsets.

**Best Fit Thresholds:**

- A function to calculate the best potential split points (thresholds) for each feature.

**Entropy and Information Gain:**

- Functions to calculate the entropy of a feature and determine the information gain from different splits.

**Random Feature Subsets and Bootstrap Sampling:**

- Functions to create random subsets of features and bootstrap samples of the dataset to introduce randomness in the model.

**Decision Tree and Random Forest Training:**

- Recursive functions to train a decision tree and a random forest model by selecting splits based on maximum information gain.

**Prediction Functions:**

- Functions to traverse the trained decision tree or random forest and make predictions on the test data.

**Model Evaluation:**

- Calculation of model accuracy by comparing predictions with actual outcomes in the test set.
