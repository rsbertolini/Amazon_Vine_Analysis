# Amazon_Vine_Analysis

## Overview of the analysis
The purpose of this project was to perform ETL process on a subset of Amazon review data to determine if there is any bias towards paid vine reviews vs unpaid reviews.

## Results

### Total Reviews
- Vine Reviews = 35 vs Non-Vine Reviews = 4957

![Total_Reviews](/Images/Total_Reviews.PNG)

### Total 5 Star Reviews
- 5 Star Vine Reviews = 18 vs 5 Star Non-Vine Reviews = 1963
![5Star_Reviews](/Images/Total_5Star.PNG)

### Percent 5 Star Reviews
- Percent 5 Star Vine Reviews = 51% vs Percent 5 Star Non-Vine Reviews = 40%
![Percent_5Star](/Images/Percent_5Star.PNG)

## Summary:
There appears to be a positivity bias for paid Vine reviews in our subset because the paid Vine reviews accounted for over 50% 5 star ratings versus a 40% 5 star rating rate for 
non-Vine reviews.  However, our Vine subset of reviews amounted to only 35 reviews so a larger subset of Vine reviews may be needed to determine with greater accuracy if Vine reviews have a positivity bias or not.

Because our Vine review subset was less than 1% of our total reviews, an additional analysis we could use is to look at a greater percentage of Vine reviews.  Our subset was
limited to those reviews that were deemed most helpful and this seemed to have particularly limited the Vine reviews.  The number of Vine reviews in the total subset was 248 
but we only used 35 of the ones deemed most helpful for this analysis.
