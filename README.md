# Amazon_Vine_Analysis

## Overview of Analysis

This analysis evaluates review data for Outdoor products on Amazon and determine whether there is a bias in paid reviews compared to non-paid reviews for Outdoor products. In this analysis vine is used to denote paid reviews and non-vine is used for non-paid reviews.

## Resources
-	Software: Google Collaborate, PySpark 3.0.3, Amazon Web Services, pgAdmin 5.1
-	Dataset: Amazon Reviews US Outdoors V1 _00

## Results
- Total Vine vs. Non-Vine Reviews
 
--There is a total of 107 vine reviews 
![Total_Vine_Reviews](/Resources/Total_Vine_Reviews.png)

--- There is a total of 39,869 non-vine reviews
![Total_Non_Vine_Reviews](/Resources/Total_Non_Vine_Reviews.png)


-	5-star Vine Reviews Vs. 5-star non-Vine reviews
There is a total of 56 5-start vine reviews 

![Paid_Vine_Five_Stars](/Resources/Paid_Vine_Five_Stars.png)

There is a total of 21,005 5-star non-vine reviews

![Non_Vine_Five_stars](/Resources/Non_Vine_Five_stars.png)

-	Percentage of Vine 5-star Reviews Vs. non-Vine 5-star Reviews
52.34% of Vine reviews are 5-stars

![Percentage_Paid_5_Star_Reviews](/Resources/Percentage_Paid_5_Star_Reviews.png)

52.69% of non-Vine reviews are 5-stars

![Percentage_Unpaid_5_Star_Reviews](/Resources/Percentage_Unpaid_5_Star_Reviews.png)

## Summary

When comparing the percentages of paid 5-star reviews with unpaid 5-star reviews, it can be concluded, based on this data set, there is not a positivity bias for reviews in the Vine program. The percentage of Paid vs. Unpaid is extremely close, 52.34% vs. 52.69%, respectively. The unpaid 5-star review show to be even lightly higher compared to the paid vine program. It is recommended to conduct the same analysis on each of the vine programs used in other departments, i.e. Pet-Products, Shoes, Electronics, etc. to further investigate whether or not there is a positivity bias from reviews in the Vine program. Moreover, the analysis from each departments should be compared to evaluate if vine programs for certain departments have more or less pervasive bias. 
