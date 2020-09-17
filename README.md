# boston_housing
### Background:

As a project for Data Science bootcamp, this a exploratory data dnalysis of Boston Housing dataset, using Linear Regression algorithm.  
[Boston Housing](https://scikit-learn.org/stable/datasets/index.html#boston-dataset) is a dataset loaded and available on sklearn package.

### Packages:
- pandas
- numpy
- sklearn
- matplotlib
- seaborn
### Exploratory Data Analysis
Distribution of the prices:  
![Distribution Plot](https://raw.githubusercontent.com/r7asmu7s/boston_housing/master/plots/price_displot.png)  
Correlation Heatmap of the attributes to the prices:  
![Heatmap](https://raw.githubusercontent.com/r7asmu7s/boston_housing/master/plots/corr_heatmap.png)
### Predicting Test Data
Comparision of scattered real test data and predicted prices, which looks close to Least Squares Regression Line in plot below:  
![Predictions](https://github.com/r7asmu7s/boston_housing/blob/master/plots/predict.png?raw=true)
### Evaluating the Model
MAE: 7.2281  
MSE: 79.8130  
RMSE: 8.9338  
R2: 0.6122  
### Residuals
Comparision of residuals to make sure it looks normally distributed.  
![Distribution Plot](https://github.com/r7asmu7s/boston_housing/blob/master/plots/residuals.png?raw=true)
### Conclusion
Based off the Correlations Table extracted from the dataset, the most correlated feature is NOX / (Nitric Oxides Concentration (Parts per 10 Million).  
Holding all other features fixed, a 1 unit increase in other remaining features results in changes of the TARGET price which can be seen below:  
![Coefficients](https://github.com/r7asmu7s/boston_housing/blob/master/plots/coeff.JPG?raw=true
)
