# MechaCar_Statistical_Analysis-
## Overview
The goal of this project is to analyze metrics and determine if our analysis can assist the manufacturing team in resolving production issues. The metrics we are analysing include; vehicle length, weight, spoiler angle, ground clearance, all wheel drive(AWD) capabilities, miles per gallon(MPG), and the injection coils pressure per square inch(PSI). 
## Linear Regression
This portion of the project I used linear regression to predict MPG. 
![This is an image](https://github.com/weise142/MechaCar_Statistical_Analysis-/blob/main/images/Summary%20stats.png)
- The summary statistics show the intercept, vehicle length, and ground clearance provide a non-random amount of variance to the MPG values.
- We can state that the slope is not 0 because the level of significance for a p-value is 0.05 and these statistics show the p-value is very small. Since our null hypothesis states that the slope is 0 and we can reject the null hypothesis this proves the slope is not 0.
- The linear regression model does effectively predict MPG for Mechacar's prototypes. An adjusted R-square of 0.6825 concludes the linear model predicts mpg relatively well and multiple R-squared increases as more variables are passed through the regression model.
## Suspension Coils
![This is an image](https://github.com/weise142/MechaCar_Statistical_Analysis-/blob/main/images/lot%20summary%20table.png)
The summary stats on the manufacturing data on suspension coils indicates that current manufacturing standards meet the 100 PSI variance limit. Although all three lots meet the requirements, lot 3 does have a high variance and risks the possibiliy that the a portion of the lot does not meet PSI requirements.
## T-Test on Suspension Coils
![This is an image](https://github.com/weise142/MechaCar_Statistical_Analysis-/blob/main/images/t-test.png)
We can see with the stats that the p-value is 0.06 is over our significance level of 0.05 meaning we fail to reject the null hypothesis, meaning we cannot reject that the sample mean may be equivalent to the true population mean. 
## T-Test on multiple lots
![This is an image](https://github.com/weise142/MechaCar_Statistical_Analysis-/blob/main/images/multi%20lot%20t-test.png)
Lot 1: We can see that the P-value for the first lot is 1 meaning it far surpasses the significance level of 0.05 meaning we fail to reject the null hypothesis.
Lot 2: For lot 2 we can see the P-value is over 0.06 meaning it exceeds the significance level of 0.05 meaning we fail to reject the null hypothesis.
Lot 3: The third lot is the only of the 3 lots whose P-value does not exceed 0.05 at 0.04. The mean of the sample is also significantly smaller in comparison to the first two lots and importantly, the confidence interval for the third lot does not include the predicted population mean.
## Study Design
Another study that can be performed to test Mechacar against its competiton is a linear regression comparing city and highway fuel efficiency. Having better MPG than competitors between both city and highway is important for consumers as prices continue to rise in all aspects of life, houses in suburbs are getting higher meaning more people are living in cities, and transportation costs make up a large portion of peoples expenses. The dependent variable or the study would be City and Highway fuel efficiency, while the independent variables could be Horse Power, Vehicle Weight, all wheel drive capabilites, air intake, and oil consumption. We have some information that can be used but we would need to collect additional data to better understand our study.
