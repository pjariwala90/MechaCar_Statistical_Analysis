# MechaCar_Statistical_Analysis

## Linear Regression to predict MPG


The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. That is to say, the vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype. Conversely, the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.

The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.

This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. Relatively speaking, his multiple regression model does predict mpg of MechaCar prototypes effectively.
![deliverable 1](https://user-images.githubusercontent.com/86641997/135331039-a7dd3be0-bc12-4281-91e7-d7170ed3092c.png)



## Summary Statistics on Summary Coils

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

When looking at the entire population of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

Similarly, but significantly more consistent, Lot 1 and Lot 2 are well within the 100 PSI variance requirement; with variances of 0.98 and 7.47 respectively. However, it is Lot 3 that is showing much larger variance in performance and consistency, with a variance of 170.29. It is Lot 3 that is disproportionately causing the variance at the full lot level.

![deliverable 2](https://user-images.githubusercontent.com/86641997/135331215-a4b993f4-20c6-4f1b-b633-ed6d7562927c.png)

## t-test on Suspension Coils
The results of the t-test analysis reveals that the p-value for all lots is 0.06028 which is outside the signifigance level of 0.05 resulting in a confidence interval of 93.972%. Based on this prediction, there is not sufficient evidence to reject the null hypothesis. It may be stated that the dataset mean and the population mean are statistically similar. Also, the analysis predicts that the suspension coils dataset is statistically representative of the population mean.


![deliverable 3](https://user-images.githubusercontent.com/86641997/135331390-0dd67e01-d2ea-4564-910c-40d63457a0a9.png)

## Study Design: MechaCar vs Competiiton
The plan is to design the MechaCar vehicle to perform better than the general marketplace vehicles. To accomplish this goal I believe atttention is best served improving the fuel efficiency of the MechaCar. Data needs to be gathered for all MechaCar manufacturing designs, in addition to the current six variables from this analysis. Additional data could include weather conditions, i.e. wind sheer, rain, heat, etc. Varying distances of short trips and long trips are also needed to determine fuel efficiency, as well as fuel efficiency over time. The dataset must include general marketplace competitor's data for comparison.

What metric or metrics are you going to test?
The data will meet the following metrics:

All data is to be numerical
Data samples will be as large as possible
Data samples need to be randomly selected
Variance of data needs to be similar
What is the null hypothesis or alternative hypothesis?
HO: There is no statistical difference between the competition's mpg dataset and MechaCar's mpg dataset.

Ha: The true mean of MechaCar's mpg is greater than the mean of the competitor's mpg.

What statistical test would you use to test the hypothesis? And why?
I reccomend using the t-test to compare our dataset with the competitors. The t-test has already been used for this current analysis and provided the predictions needed to take the next steps for improvement.

What data is needed to run the statistical test?
The p-value would be set at 0.05. Data that results in a prediction of a p-value smaller than 0.05 would provide predictive evidence that the null hypothesis could be rejected and state that the Ha is true. Providing evidence that the Ha is true would also predict that the MechaCar provides consistently better fuel efficiency than the competitors mpg. There is always room for error and better fuel efficiency may not happen all of the time, but at least 95% of the time.

