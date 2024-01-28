This project creates a machine learning pipeline to predict if the first stage of the Space X mission will land given the data from the preceding labs.

The whole project is in the Jupyter Notebook. The Notebook guides you through each step and includes all required Python Code.

The sections in the Notebook include:
1. Import necessary Python Libraries
2. Write a Function to plot the Confusion Matrix
3. Load the Dataframe into Pandas
4. Use the function train_test_split to split the data X and Y into training and test data
5. Calculate the accuracy of the test data using the method Score
6. Plot Confusion Matrix from True Labels and Predicted Labels
7. Create a support vector machine object
8. Create a decision tree classifier object then create a GridSearchCV object tree_cv with cv = 10
9. Fit the object to find the best parameters from the dictionary parameters
10. Plot Accuracy of Each Model: LogReg, SVM, TREE, KNN
