# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

-Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - Vehicle Length: 2.60e12
  - Vehicle Weight: .0776
  - Spoiler Angle: .3069
  - Ground Clearance: 5.21e-08
  - All Wheel Drive (AWD): .1852
  - Non-random amount of variance to mpg: Vehicle Weight, Spoiler Angle and AWD
  
-Is the slope of the linear model considered to be zero? Why or why not?
  - The slope of the linear model is not considered to be zero because there are statistically significant  relationship between Vehicle Length and Ground Clearance on MPG at the .0001 level. 
  
-Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - R-Squared value: .7149
  - The R square value indicates that around 71% of predictions will be effective using this linear model. It does predict MechaCar prototypes effectively, but there is still around 29% chance predictions will not be correct.
  
## Summary Statistics on Suspension Coils

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  -All Manufacturing lots in total: When grouped together, the variance on PSI is 62.29356. This does not exceed the 100 pounds per square inch. 
  -Each lot individually: Lot 1 and Lot 2 do not exceed the 100 pounds per square inch with their variance, but Lot 3's PSI variance is 170.28, which exceeds the 100 pounds per square inch by around 70. 
  
## T-Tests on Suspension Coils

-PSI across all manufacturing lots: t = -1.8931, df = 149, p-value = 0.06028
-PSI Lot 1: t = 0, df = 49, p-value = 1
-PSI Lot 2: t = 0.51745, df = 49, p-value = 0.6072
-PSI Lot 3: t = -2.0916, df = 49, p-value = 0.04168

- The p-value for all lots is .06 which is not statistically significant at the .005 level. 
- The p-value for Lot 3 is significant at the .05 level however, meaning we can reject our null hypothesis for only lot 3. 

## Study Design: MechaCar vs Competition

This study will look at the safety ratings of the MechaCar versus its competition. This study will look at the overall safety ratings according to the Insurance Institute for Highway Safety (IIHS) and their crash test ratings. These ratings are based on four factors to include; measurements taken from crash test dummies, survival space, airbags and seat belt effectiveness. 

### Metrics to Test
- Overall safety rating
- measurements from crash test dummies
- survival space
- airbags
- seat belt effectiveness

### Null Hypothesis

-Ho: There is no statistical difference between MechaCars safety rating and the competitions safety rating.

### Statistical Test

-Two sample t-test: Is there a statistical difference between the distrubtion means from two samples?

### Data needed to run test

-IIHS Safety ratings data




  