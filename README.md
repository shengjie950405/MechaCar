# MechaCar
## Linear Regression to Predict MPG
<img width="755" alt="Screenshot 2022-12-14 at 6 14 37 PM" src="https://user-images.githubusercontent.com/111814578/207735768-bfe08150-6de1-4921-804d-add6e92b8400.png">

- Vehicle_length, ground_clearance and intercept provided a non-random amount of variance to the mpg values in the dataset.
- The p-value of our linear regression analysis is 5.35 x 10-11, which is much smaller than our assumed significance level of 0.05%. The slope of the linear model is not zero. Thus, we can tell that there is sufficient evidence to reject our null hypothesis.
- This linear model predict mpg of MechaCar prototypes effectively. Because from our linear regression model, the r-squared value is 0.68, which means that roughly 68% of all MPG predictions will be correct when using this linear model. 

## Summary Statistics on Suspension Coils
<img width="346" alt="Screenshot 2022-12-14 at 6 19 40 PM" src="https://user-images.githubusercontent.com/111814578/207736449-725f33b1-f02e-4de5-bcb3-ac4b53d9b29e.png">
<img width="494" alt="Screenshot 2022-12-14 at 6 20 05 PM" src="https://user-images.githubusercontent.com/111814578/207736468-4b342a57-3261-4beb-8c31-455d0b87872b.png">

The total variance is 62.29 and it doesn't exceed the 100 PSI variance based on design specifications. 
But, in those three lots, lot 3 exceeds the design specifications of 100 PSI.

## T-Tests on Suspension Coils

- The p-value of total lots is 0.06, this is higher than our assumptions of significance level of 0.05%. There is significant different between population mean and mean of the total.
- The p-value of lot 1 is 1, which is much higher than our assumptions of significance level of 0.05%. There is significant different between population mean and lot 1. We have enough evidence to reject the null hypothesis and state that the two means are statistically different.
- The p-value of lot 2 is 0.6, which is much higher than our assumptions of significance level of 0.05%. There is significant different between population mean and lot 2. We have enough evidence to reject the null hypothesis and state that the two means are statistically different.
- The p-value of lot 3 is 0.04, which is lower than our assummptions of  significance level of 0.05%. There is no significant different between population mean and lot 3. We don't have enough evidence to reject the null hypothesis.

![Screenshot 2022-12-14 at 6 25 19 PM](https://user-images.githubusercontent.com/111814578/207736950-dcd0893c-4abd-4e39-88e6-1b4f4d32bcbe.png)

## Study Design: MechaCar vs Competition
I will design a T-test to compare the safety rating of MechaCar with competitors. The Null hypothesis there is no difference between mean of MechaCar and rest of competitors. And the alternative hypothesis will be there is a significant difference between mean of MechaCar and competitors.


