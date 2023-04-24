LINEAR REGRESSION: 
Linear regression is a statistical method for modeling relationships between a dependent variable with a given set of independent variables.
Simple linear regression is an approach for predicting a response using a single feature.
In order to provide a basic understanding of linear regression, we start with the most basic version of linear regression, 
i.e. Simple linear regression.

REGRESSION-PREDICTION-OF-DIAMONDS: 

I'm predict diamonds Dataset using Simple Linear Regression: 
START: I get dependent variable is diamonds columns and independent variable is wrist columns.
Then unwanted coulums are deleted using DROP key.
locate and reshape the values of X and Y. 
Then using the MatPlotLib to visible a Scatter plot of X,Y. split the values of x and y using train & test methods.
Thus the simple linear regression was implemented. Then using sklearn find the mean squard error and mean absolute error. [mean_squared_error(y_test,y_predict)=2372901.2792871664] 
[mean_absolute_error(y_test,y_predict)=1002.1962617257723].
