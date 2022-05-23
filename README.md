# Amazon_Vine_Analysis

## Overview
This project focused on reviewing a Amazon review dataset utilizing PySpark. The dataset contained US Pet Products Review data and was also uploaded to a Amazon RDS. The actual analysis involved looking at the Vine review data to see if there is any bias toward favorable review from members of the Amazon Vine review program. 

![Results](/Resources/1.PNG)

## Results
After filtering the review dataset for reviews with 20 or more total_votes, where the number of helpful_votes to total_votes is greater than 50% and if they participated in the the Vine review program.

* In the US Pet Products dataset there were 170 Vine Reviews and 37840 non Vine Reviews.

![Results](/Resources/1.PNG)

* There 65 five star Vine reviews and 20612 five star non Vine reviews.

* 38% of Vine Reviews were five stars and 54% of non Vine reviews were five stars.

![Results](/Resources/1.PNG)

## Summary
Overall, there is no evidence of bias toward favorable reviews from members of the Amazon Vine review program. With only 48% of the vine reviews being five stars compared to 54% of the non vine reviews being five stars. This shows that vine reviews do not tend to be more favorable. 

An additional analysis could be to also filter for verified purchases to help cut down on the number of reviews that did not purchase the product. This could help by showing only the reviews that actually purchased the product. This could help counter fake or falsified reviews. 
