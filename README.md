# Amazon_Vine_Analysis 
## Overview
This analysis uses Amazon product review histories, specifically concerning automotive products.  The data consisted of the reviews themselves, as well as their dates of entry, product & customer identifiers, star ratings, and importantly for our purposes, wether or not they were participating in a sponsored reviw program known as "Vine".
Is the "Vine program differentiating itself from the unsponored reviews on Amazon?  To get insight into that question we broke down the data to see how easy it is to get a 5 star review from both types of reviewer.
## Results
<p align="center">
   <img width="600" height="200" src="https://user-images.githubusercontent.com/111530580/208141774-63f3a265-e9af-4c1b-b05d-389847e84c27.png">
</p>
The data frame sample above is the raw information that was used to gain our insights.  
It included over 3.5 million rows of data.  It was filtered down to only include products which had more than 20 revies, and then further to reviews with at least 50% reported as being helpful.  This lowered our count to 24,824 reviews.
Of these two categories, the breakdown was as follows:

### Vine Reviews

  - Total = 82
  - 5 Star Total = 33
  - 5 Star Percentage = 40.24%
  
### Non-Vine Reviews

  - Total = 24,724
  - 5 Star Total = 12,807
  - 5 Star Percentage = 51.76%
  
## Summary
The data gathered points to the conclusion that there is some more scrutiny placed into reviews that are participating in the "Vine" program.  They were 11.5% less likely to offer a 5 star review than their non participatin counterparts.
However, the amount of data in the "Vine" program was relatively samll at only 82 data points when compared to the others 24,724.  One could improve on the analysis by getting more data.  This could be achieved by both increasing the date ranges of the data gathered and including the analysis of other categories of products in the automotive category.  If these other data sets reinforced the conclusions drawn here, then the case for "Vine" reviews being more thorough would be harder to deny.  
  

