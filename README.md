# Trulia-Price-Prediction-USA

Problem:

The US real estate market is worth 33 Trilion dollars. For the shareholders in the industry (sellers, buyers, and investors) one of the biggest questions is what is the home worth and which factors play a big role in determining this.

Approach:

Using Machine Learning, data cleaning and data analysis, I will aim to solve this problem and provide actionable insights.

Results:

After completing our analysis, I can conclude that this dataset was able to produce a very respectacle R2 score ( 0.4917 on the test set and 0.5276 on the training set), but is not ideal for this purpose. By using the .coef_ and .feature_importance_ features on the Linear Regression and Random Forest Regression models I was able to find some very interesting insights comparing our variables to the target variable Price. 

Looking at the Feature Importance graph in cell 333 of the Jupyter Note, you can see that for our Random Forest Regression, the variables Last_Sold_For, Bath, Last_Tax_Assesment and Sqr_Ft, had a big hand in predicting the target variable price. So when deciding to buy or sell a home, homeowners and buyers want to emphasize these variables in their decisions. 


Reviewing the information for the .coef_ variable (cell 444), there is a wealth of valuable information. Looking at some of the variables I mentioned above, we can see that the Bath variable had a .coef_ of 206,276.46 USD, meaning that for every bathroom a listing has, you can expect an 206,276.46 USD increase in cost for that home. 

For the Sqr_Ft variable, you can see that for every square foot of the unit there is an increase of 0.08 USD. So generally the bigger the unit the more expensive it will be. 

In conclusion, after employing different regression models, and hypertuning several parameters, I have determined that our dataset is able to predict price in a fairly decent capability and  I was able to find some very insightful data regarding Trulia home listings in the US, and I do hope to be able to apply this information, should I choose to buy or sell a home in the near future. 
