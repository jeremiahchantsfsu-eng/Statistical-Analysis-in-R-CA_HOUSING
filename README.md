# Statistical-Analysis-in-R-CA_HOUSING

This assignment uses linear regression to predict California house values based on numerical data. It covers the full modeling lifecycle: importing data, partitioning it into training and testing sets to ensure validity, and evaluating the results to understand which variables drive home prices.


# Overview (Deeper)
This assignment focuses on building a predictive model to understand the factors influencing California’s real estate market. By using the lm() function in R, you are performing a multiple linear regression that identifies the mathematical relationship between a house's value and numerical predictors like median income, house age, and location coordinates. The process begins with data partitioning, where the dataset is split into a training set to build the model and a testing set to validate its accuracy. 

This step is crucial because it proves the model can actually predict prices for houses it hasn't "seen" before, rather than just memorizing the original spreadsheet.Beyond just calculating a prediction, the assignment emphasizes model diagnostics through statistical summaries and visual plots. By analyzing the $R^2$ value and p-values, you determine how much of the price variance is explained by your variables and which factors are statistically significant. Visual tools, such as the Scale-Location and Residuals vs Fitted plots, allow you to verify that the model's mathematical assumptions—like constant variance and linearity—are met. This comprehensive approach ensures that the resulting model is not only statistically sound but also a reliable tool for understanding the economic drivers of housing costs.


# Road Map

Data Preparation: I imported the CaHousing.xls dataset and isolated the numerical variables to ensure the data was in a compatible format for a linear regression algorithm.Data Partitioning: I split the data into an 80% training set to develop the model and a 20% test set to evaluate its predictive performance on unseen data.Model Building: Using the training dataset, I applied the lm() function to regress median_house_value against all other numerical predictors to identify their mathematical relationships.Model Evaluation: I analyzed the $R^2$ value and diagnostic plots, such as the Scale-Location plot, to assess the model's accuracy and verify that the statistical assumptions of linearity and constant variance were satisfied.








