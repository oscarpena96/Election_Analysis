**Election_Analysis_Challenge**
=============


Objective
========

1. Navigate trough Git Bash 
2. Read and extract data from csv to python
3. Get to know each data type of python
4. Create, execute and modify python files
5. Import and export data into python
6. Know the different packages that python offers and start using them

Analysis
======
1. Get all the different names from counties and candidates trough a for loop
2. Calculate the number of votes for each candidate and county
3. Calculate the percentage of votes for each candidate and county
4. Determine which county and candidate has de most votes 
5. Determine who was the winner between the candidates and which county had the most votes

# Overview of the election audit 
- The dabase comes from the election from 2018 where Diana DeGette faced Charles Casper Stockham and Raymon Anthony Doane, the **purpose** of this analysis was to determinate the winner trough counting the votes and seing who came victorious. 

Tools
=====
Software: Python 3.9.7 and Visual Studio Code v1.692.2
Data: election_results.csv (provided by Tec de Monterrey)

Results
=======
1. Total Votes
Election Results

Total Votes: 369,711
2. Votes by County

County Votes:
Jefferson:10.5% (38855)
Denver:82.8% (306055)
Arapahoe:6.7% (24801)

3. Largest County Turnover: Denver

4. Votes for each candidate and percentage
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

5. Winner of election
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

The county that provided the majority of votes was Denver (82.8%) from the total (369,711).
The winner for the election was Diana DeGette with a total of 272,892 winning with more than the sum of her competitors.

**Summary**
=======
The code worked perfectly for this election but there is 2 different ways that we can modified it to get better results
1. Colabella (2022) mentions that we can give different weight to each county, altough he talks about the presidential election we can put that idea in to use with our study determining wich county has more weight and decide the winner based on the votes and weight from each county.
2. We can puth both the coutny and candidate in the same loop so it´s just one loop and it runs faster
