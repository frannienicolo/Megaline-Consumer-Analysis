# Megaline-Consumer-Analysis
For this project, I will be working with dataset titled 'user_behavior' which contains 5 columns: calls (number of calls), minutes (total duration of the calls), messages (number of test messages), mb_used (internet traffic used in mb), and is_ultra (0 = customer has Smart plan, 1 = customer bas ultra plan).

The goal of this project is to design a model that can predict which plan (Smart or Ultra) a customer should register for based on their usage of the features described above using the data in the user_bahvior dataset.

First I will split the dataset into three (test, train, and valid). Train will be used to tune the model and I will compare the model scores to those of the valid set. Since this is a binary classification task, I will be tuning models using the Decision Tree Classifier, Random Forest Classifier, and Logistic Regression. After determining which model returns the highest, most effective valid score in comparison to the train score, I will test the model using the test data to see how well it performs. Lastly, I will perform a sanity check.
