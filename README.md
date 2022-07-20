# Election_Analysis

## Module 3 Challenge ~ PyPoll with Python
---
## Overview of Project
- Practicing using Python dictionaries, we will create scripts in Visual Studio Code that will read, write, and store data from a file and generate a vote count report. The election commission requested additional data to complete the audit, so we will practice writing decision statements to apply our knowledge of variables and arrays. It is important to understand the difference between Python data types, such as integers, floating-point decimal numbers, and strings. This would allow us to draw results and make complex comparisons when we perform mathematical operations. Additionally, we will utilize Boolean and logical operators to create decision and repetition statements, and ultimately make data structures like lists, tuples, and dictionaries. 
- This module also introduces how to navigate GitHub, create repositories, and use the terminal application to access the command line in GitBash.

### Purpose of Election-Audit
- In this challenge, we are working with Tom and the Colorado Board of Elections to gather an election-audit of the tabulated results for the U.S. congressional precinct in Colorado. Extracting data from the election_results.csv file, I am tasked to find...
  1. the total number of votes cast
  2. make a complete list of candidates who received votes
  3. the total number of votes each candidate received
  4. the percentage of votes each candidate won
  5. and determine the winner of the election based on popular vote
  
---
### Results: 
<img width="333" alt="Deliverable1" src="https://user-images.githubusercontent.com/68654746/180044138-de9c3e39-aca3-4e7d-a8d5-38c449d1ff7c.png">

**Deliverable 1 ~ The Election Results Printed to the Command Line & Saved to a Text File**
  1. How many votes were cast in this congressional election?
      
      There were 369,711 votes cast in the election. 
  2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
      - Jefferson county received 10.5% of the vote and 38,855 number of the votes. 
      - Denver county received 82.8% of the vote and 272,892 number of the votes. 
      - Arapahoe county received 6.7% of the vote and 11,686 number of the votes. 
  3. Which county had the largest number of votes?
      Denver had the largest number of votes.
  4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
      - Charles Casper Stockham received 23% of the vote and 85,213 number of the votes. 
      - Diana DeGette received 73.8% of the vote and 272,892 number of the votes.
      - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of the votes.
  5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
      
      The winner of the election was Diana DeGette. She received 11,606 number of the votes and 73.8% of the vote.
### Summary of Election-Audit 
Now that we successfully delivered an election-audit to the Colorado election commission, we can make a business proposal to provide these services again in the future. By automating the process again using Python, we can easily generate a vote count report for any future elections. 
    
  - One modification we can perform is changing the county data to represent the weights of the electoral college votes. This would depict how strong or weak the local congressional elections will influence the U.S. congressional elections.
    
  - A second modification we can make is furthering our mathematical computations to determine if the winning candidate had supermajority. The criteria for popular majority vote is having 50.1% or more of the total votes. 
