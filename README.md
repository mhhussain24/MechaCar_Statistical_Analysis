# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
mpg: 0 < .05, statistically significant, non-random amount of variance
vehicle length: 0 < .05, statistically significant, non-random amount of variance
vehicle weight: .08 > .05 not statistically significant, random amount of variance
spoiler angle: .31 > .05 not statistically significant, random amount of variance
ground clearance: 0 > .05 statistically significant, non-random amount of variance
AWD: .19>=.05 not statistically significant, random amount of variance

All of the slope slopes of the varaibles are shown to be non-zero. The multiple linear regresssion formular for mpg results in a non-zero slope, even if xertain variables are close to zero.

R-squared is not the only variable to predict MechaCar prototypes, so more variables included in the dataset would give a better picture. However, based on the R-squared of .7149, we can assume the dataset allows us to predict mpg of mechacar prototypes effectively. 

! [Image1](R_Analysis/Image1.png)
! [Image2](R_Analysis/image2.png)

## Summary Statistics on Suspension Coils
The variance for the total manufacturing lot is less than 100. It is 62. This is within the design specification, but Lot 3 is 170, which is greater than 100 and does not meet specifications. Therefore, the current manufacturing data meets the design spefication in total, but not inidividually. 

! [Image3](R_Analysis/image3.png)
! [Image4](R_Analysis/image4.png)

## T-Tests on Suspension Coils
Total manufacturing lot is not statistically significant form the normal distribution. The mean falls in the 95% confidence interval. For Lot 1 and 2, we can say the same. However, for Lot 3 we assume that it is significantly significant from the normal distribution. However, the mean falls within 95% confidence interval as well. 

! [Image5](R_Analysis/image5.png)
! [Image6](R_Analysis/image6.png)

## Study Design: MechaCar vs. Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
1. We should be testing metrics such as horsepower and safety ratings.
2. The null hypothesis is that safety rating's mean is zero, and the alternative is that it is non-zero.
3. The test the hypothesis we would use the multiple linear regression statistical summary as it shows us the impact of variables on safety ratings.
4. The data needed to run the statistical test would be a random sample of n > 30 of different variables like safety ratings, horsepower, highway fuel efficiency. 