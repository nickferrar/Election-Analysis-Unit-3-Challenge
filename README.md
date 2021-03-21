# Election-Analysis-Unit-3-Challenge

## 1. Overview of Election Audit

The purpose of this audit is to read the statewide election data off of a CSV file and determine:

How many total votes were cast
How many votes came from each county
The percentage of the vote total that came from each county
The largest county turnout
How many votes each candidate received
The percentage of the total votes each candidate received
The winning candidate

## 2. Election-Audit Results

Answering the above questions:

There were 369,711 total votes cast in the election

Jefferson had 10.5% of the total (38,855 votes)
Denver had 82.8% of the total (306,055)
Arapahoe: had 6.7% of the total (24,801) 

**Denver had the largest turnout**

Charles Casper Stockham had 23.0% of the total vote(85,213)
Diana DeGette had 73.8% of the total vote(272,892)
Raymon Anthony Doane had 3.1% of the total vote(11,606)

**Diana DeGette is the winning candidate**

## 3. Election-Audit Summary
This code can be used for any election with a few modifications. This code works assuming that the second column in the file that it's reading is the county and the third column 
is the candidate's name. However, we can modify the code to find which column contains the candidate's name by checking to see which column has a combination of blanks and 
characters since the county will be a single string.

Also, this election simply takes a popular vote winner. In Canada, while each riding would be decided by the candidate who receives the most votes in that riding, parliament 
would give power to whichever party wins the most ridings. The US presidential election also uses a system similar to that where the winner of each state gets all of the 
electors of that state, which implies that the overall popular vote winner may not be the winner of the election. To modify the code for this assignment, we would have to keep a 
tally of which candidate is winning the most seats or states and not just the overall vote count of each candidate.
