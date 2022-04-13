# Amazon_Vine_Analysis

## Overview
The purpose of this analysis is to identify if there is any bias that exists in Vine review ratings for watches. There is potential bias because Vine reviewers have a financial relationship with Amazon, but it may not exist. This analysis is executed using PySparks and Google Colaboratory.

## Results
- How many Vine reviews and non-Vine reviews were there?
  -  There are 47 Vine Reviews and 8,362 non-Vine Reviews.
  ![Number of Reviews](https://github.com/kramerkyle/Amazon_Vine_Analysis/blob/main/Number%20of%20Reviews.png)
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There are 15 5-star Vine reviews and 4,332 non-Vine Reviews.
![5 Star Reviews](https://github.com/kramerkyle/Amazon_Vine_Analysis/blob/main/Number%20of%205%20Star%20Reviews.png)
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - Only 31.91% of the Vine reviews were 5 stars versus the 51.81% of the non-Vine reviews.
![5 Star Percentage](https://github.com/kramerkyle/Amazon_Vine_Analysis/blob/main/5%20Star%20Percentage.png)

## Summary
This analysis does not reveal any indication of bias. In fact, it seems that these reviews are more balanced than non-paid reviews. This could be because of fraudulent 3rd-party reviews, but it is more likely that these Vine reviewers are less emotionally invested in their reviews.

An additional analysis that would be informative is to verify these results through a t-test between the samples. Alternatively, a weight can be associated with each of the reviews according to the number of helpful votes that were assigned to it.
