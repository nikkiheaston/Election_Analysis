# Election Analysis in Python
## Overview of the Project
### Purpose
The purpose of this project is to analyze voting and election information, specifically for 3 candidates and 3 counties (Jefferson, Denver, and Araphaoe), as presented in the csv file that accompanies this file. 

### Results
- The total number of votes cast in this election was 369,711.
- Each county's vote count and percent of the total vote is as follows:
  
  Jefferson: 38,855    (10.5%)
  
  Denver:    306,055   (82.8%)
  
  Arapahoe:  24,801    (6.7%)
  
- Denver had the largest number of votes.
- Each candidate's vote count and percent of the total vote is as follows:

  Charles Casper Stockham: 85,213  (23.0%)
  
  Diana DeGette:           272,892 (73.8%)
  
  Raymon Anthony Doane:    11,606  (3.1%)
  
- The winner in this election was Diana DeGette who received 272,892 votes, accounting for 73.8% of the total vote.

### Summary
I propose that, with some modification, the Python code used to conduct this analysis can be used in any election. 
1. One way is to update the counties list and dictionaries with whatever geographical region is being analyzed. By district, city, region, state, nation, etc. Updating variable names with more generic terms would allow for any geography to be examined.



2. This code can also be modified to analyze initiatives or measures. In place of candidates, we can create a dictionary with keys representing each measure, and values representing "Yes" or "No" votes to those measures. Votes would be totaled by an if statement with Boolean values - "Yes" meaning "True" and "No" meaning "False".
