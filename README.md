# ElectionAnalysis
**Overview of Election Audit**
The purpose of this election audit analysis is to review three main things; voter turnout for each county, the weighting of which counties contributed the most votes, and finally the county with the largest voter turnout. 

**Election-Audit Results**
- There were a total of 369,711 votes cast in this congressional election.
- Jefferson county represented 10.5% of the votes with 38,855. Denver held 82.8% of the votes with 306,055, and finally Arapahoe had 6.7% of votes with 24,801 votes cast.
- Denver had the largest amount of votes.
- Diana DeGette won the election with 272,892 or 73.8% of votes. She was followed by Charles Casper Stockham with 85,213 votes or 23%. In last place was Raymon Anthony Doane with 11,606 votes or 3.1% of the total.
- A screenshot of the full terminal report is below:

![terminal](https://github.com/ozzirk/ElectionAnalysis/blob/main/Analysis/Terminal%20Results.png?raw=true)

**Election-Audit Summary**
In summary, this script can help the election commission to quickly process the data and summarize it in future elections. Some modifications can be made to adjust the script to allow it to work in more situations. 
1. To select the winning county, the logic statement found the county with more than 50% of the votes. This can be adjusted to find the county with the highest number of votes, rather than the highest percentage of votes.
2. The dictionaries that carry the county and voter information can be easily changed with a new raw file, allowing minimal modification to the script itself.
3. We can incorporate additional details from the voter groups like political affiliation, or report on candidate rankings within each individual county to see patterns in each geography.
