# Election-Analysis
# Overview of ELection Audit
The purpose o fthe Election Audit Analysis was to use python to analyse and calculate the election results from the csv file provided. The election results calculated the winner among the candidates by what percentage the winner has won over other candidates. Moreover we analysed the elction results with respect ot each county and by what percentage the largest county turnover had won  
# Election Audit Results
From the Election audit result we can summarise that the winner is Diana DeGette by an election percentage of  73.8% and a vote count of 272,892
* A total of 369,711 were cast by the voters 
* Denver had a vote count of  82.8% (306,055)
* Arapahoe had a vote count of 24,801 which is 6.7% of total count
* Jefferson had a vote of (38,855) which is 10.5% of total count
* The county with most number of votes is Denver election percentage of   82.8% (306,055)
* Winner is Diana DeGette by an election percentage of  73.8% and a vote count of 272,892
# Election Audit Summary
The python script provided for the election results can be used for the future elections provided the csv file uses the same format for entering the county, candidate and election results. To use a different election csv file change the with new file at the same location and change its name in the line after import statement . Replace election_results.csv with the a file that a file that you want to perform the results
  Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
