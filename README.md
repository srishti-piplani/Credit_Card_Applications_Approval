# Credit Card Application Approval Prediction

The credit card applications are ever increasing and it has become difficult for companies to manually analyze each of the applications. There is a need of an automated and high quality credit card approval prediction system. Machine learning can help to automate this process and save time for the companies.

The dataset has been taken from the UCI Machine Learning Repository.
[Credit Card Approval Dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval)

In this project, logistic regression has been used for predicting the credit card approval prediction.
Approach followed:
- Data exploration to find potential issues
- Fix NULL values using mean imputation/ replacing with most frequent values
- Drop unnecessary columns, non numeric to numeric conversion, normalization
- Building Logistic Regression Model
- Evaluating performance using confusion matrix and score
- Hyperparameter Optimization using Grid Searching

#### Packages used:
- Numpy
- Pandas
- sklearn
- matplotlib

With hyperparameter optimization, we were able to improve the accuracy to about 85%. Such a predictor has wide applications in the banking industry and can be studied further to reveal important insights. The next step is to experiment with hyperparameter optimization and explore other models for this problem.
