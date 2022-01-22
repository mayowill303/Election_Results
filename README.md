# Election_Results

I assisted the board of elections with an audit of the election results for U.S. Congressional precinct in Colorado. I created reports on the election results as follows:

1. Total Votes
2. Total Votes per each candidate
3. The percentage of votes per each candidate
4. Winner of the election based on the popular vote

Rather than using Excel, the board of elections wants to know if there is a way to automate this process. Python was the perfect solution for this.  I performed the analysis using Python 3.9.7 via VS Code  with Git Bash to push to GitHub.

Overview of Election Audit: 
The purpose of this election audit analysis is to submit the election audit results to the election commission.  Going through the audit helped me to understand creating scrips, performing mathematical operations and decision statements to produce screen outputs.
Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

1. 369,711 total votes were cast in this congressional election

2. County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)	

3. Denver had the largest number of votes.

4. Candidate Votes:
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

5. Diana DeGette won the election with 272,892 votes and 73.8% of total votes.

This script can be used for any election with the below modifications:
- Add, edit and delete candidates in dictionaries or lists
- Add, edit and delete counties in dictionaries or lists
