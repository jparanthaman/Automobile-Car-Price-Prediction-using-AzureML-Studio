# Automobile-Car-Price-Prediction-using-AzureML-Studio
Using Azure Machine Learning studio, To create a Linear Regressor model to predict the price of an automobile with its features (like horsepower,peakrpm,engine-type,body-style etc...).

Problem Statement: The project is to predict the Automobile Price based on the features of an automobile (horsepower,peakrpm,engine-type,body-style etc...).

The main objective behind the project is to predict the price of an automobile with its features (like horsepower,peakrpm,engine-type,body-style etc...)..For this implementation first we need to get the data in .csv format. We can use the sample data set [Automobile price data Raw.csv] provided in the platform itself. The raw data is completely spread in our blank canvas. The attributes includes make, body-style, wheel-base, engine-size, horsepower, peak-rpm and highway-mpg. Preprocessing of data is done before training and analyzing the model. The data must be clean so that the model can predict correctly. For this purpose the empty[Null] values are removed by using column dataset model. Then split the data and then pass the results to the Two Class Boosted decisions algorithm module to train the model. Finally evaluate them. Now the data is ready, constructing a predictive model consists of training and testing. We'll use our own or sample data to train the model, and then we'll test the model to see how accurately it is able to predict price of the automobile.

Project Link : https://gallery.azure.ai/Experiment/Car-Price-Estimator-Predictive-Exp-using-linear-regression

Tool used : Azure Machine Learning Studio (Classic).

Azume ML Studio: Azure Machine Learning studio is a web portal in Azure Machine Learning that contains low-code and no-code options for project authoring and asset management. It's a GUI-based integrated development environment for constructing and operationalizing Machine Learning workflow on Azure.

Steps

Demo Images :

->Data Preprocessing

![image1](https://github.com/jparanthaman/Automobile-Car-Price-Prediction-using-AzureML-Studio/assets/81980087/ab1e1874-67a7-4b6e-96c3-f0bf08f3efad)


note: The normalized losses has 41 missing values to handel that the missing value rows are dropped from the dataset.




->Feature Selection 




Note: The mentioned features are selected from the dataset as the price field depends more on these fields.

-> Training Testing Split 



Note: The dataset is splitted into training and testing data using split data. 70% of data for training and 30% of data for testing.

->Model Training Image:




Note: The model is trained to predict the price column using linear regression algorithm Linear Regression Algorithm : Linear regression performs the task to predict a dependent variable value (y) based on a given independent variable (x). So, this regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression. In the figure above, X (input) is the work experience and Y (output) is the salary of a person. The regression line is the best fit line for our model. Formula : Y_i=f(X_i, \beta)+e_i




->Model Estimation:





->Input Data For Prediction:








->predicted Price:





Demo video:

https://github.com/jparanthaman/Automobile-Car-Price-Prediction-using-AzureML-Studio/assets/81980087/cbbef281-950d-427f-92fa-282a7a38d61c


