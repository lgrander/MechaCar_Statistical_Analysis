# MechaCar_Statistical_Analysis

## Deliverable 1: Linear Regression to Predict MPG 

![Linear_Regression](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Linear_Regression.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
From the linear regression model above, Vehicle Length and Ground Clearance provide a non-random amount of variance to the MPG values.

- Is the slope of the linear model considered to be zero? Why or why not?
The slope of this model would not be considered zero. For a slope to be considered zero the observed variability in the mpg values would need to be random. This is not the case for our model.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Our Model does effectively predict mpg of MechaCar prototypes. The r-squared value of this regression is .71 meaning that the model accounts for 71.49% of the variance.

## Deliverable 2: Create Visualizations for the Trip Analysis

### Total Summary
![Total_Summary](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Total_Summary.png)

### Lot Summary
![Lot_Summary](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Lot_Summary.png)

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The variance in the suspension coils is 62.29 PSI and overall fits the specs. The variance in the PSI of Lots 1 and 2 are under 10 PSI, and do not exceed 100 pounds per square inch specs. Lot 3 does not meet the design specifications and has a variance of 170.286 PSI. 

## Deliverable 3: T-Tests on Suspension Coils

Our T-test from all lots returned a p-value of .06 with a mean PSI of 1500. We do not reject the null hypothesis because the p-value is > 0.05. 

![Test_1](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Test_1.png)

Our T-test from Lot 1 retuned a p-value of 1 with a mean PSI of 1500. We do not reject the null hypothesis because the p-value is > 0.05. 

![Test_2](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Test_2.png)

Our T-test from Lot 2 retuned a p-value of .6072 with a mean PSI of 1500.2 . We do not reject the null hypothesis because the p-value is > 0.05. 

![Test_3](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Text_3.png)

Our T-test from Lot 3 retuned a p-value of .04168  with a mean PSI of 1496.14.  The null hypothesis that the suspension coils designed in Lot 3 meet the specifications is rejected because the p-value is < 0.05, the design from Lot 3 needs to raise the PSI to meet the specs. 

![Test_4](https://github.com/lgrander/MechaCar_Statistical_Analysis/blob/main/Test_4.png)

## Study Design: MechaCar vs Competition
A statistical study of potential interest would compare the fuel efficiency of the Mechacar to that of its competitors.
- Null Hyptothesis (H0): There is no statistical difference between the fuel efficiencies of the MechaCar and competing models.

- Alternative Hypothesis (HA): There is a statistical difference in fuel efficiencies.

- Data Needed: Would need to collect city and  highway fuel efficiency data for manufacring lots as well as for the competition.

-Statistical test to be perormed: Perform one sample t-test would be used to compare the mean of a sample to the population; In this case the mean of production sample would be compared to the mean of fuel efficiency of a competition car.
