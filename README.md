# Election_Analysis

## Project Overview
The Colorado Board of Elections asked for an election audit of a recent local congressional election. Using Python and Visual Studio Code we were able to do the following:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Get a list of the counties where votes were cast.
4. Calculate the total number of votes cast within each county.
5. Determine which county has the largest voter turnout.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.61.2

## Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The counties where votes were cast were:
  - Jefferson
  - Denver
  - Arapahoe
- The voter turnout was:
  - Jefferson County was the location of 10.5% of the total votes with 38,855 votes.
  - Denver County was the location of 82.8% of the total votes with 306,055 votes.
  - Arapahoe County was the location of 6.7% of the total votes with 24,801 votes.
- The county with the largest voter turnout in this election was:
  - Denver County, which was where 82.8% of the voters, totaling 306,055, cast their votes.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote with 85,213 votes.
  - Diana DeGette received 73.8% of the vote with 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote with 272,892 votes.

## Election-Audit Summary
This election audit can be utilized in other elections, in Colorado and around the country. The same code would be applicable with some modifications in order to analyze and verify other election results. The modification explanations are as follows:

### Modification 1
The first item that would need to be modified to make the code usable for other elections is the file path locating the csv file storing the election results. It would be different, depending on the file structure and file names on the computer of the person doing the audit. Modifying this would make sure the correct information is pulled and looped through. Also, the file_to_save might need to be modified if there is already a file with the same name, or if the code user would want to call the results file something different.

![This is a picture of the code of the locations for loading the files to be analyzed and saving the results.](https://github.com/hmpowell/Election_Analysis/blob/main/Resources/loading_and_saving_file.png)

### Modification 2
The file name would also need to be modified to allow the correct election results file to be analyzed. If the wrong file is used for the data, the analysis will not be conducted on the correct election. If the file name is one that is not on the computer in the folder specified in modification 1, then the code will not run.

![This is a picture of the code which loads the csv file.](https://github.com/hmpowell/Election_Analysis/blob/main/Resources/reading_csv_file.png)

### Modification 3
If there are a different number of columns in the election results file, then the column numbers would need to be modified so the correct column is being looped through for each row when counting the votes.

![This is a picture of the code which contains the column numbers that should be looped through.](https://github.com/hmpowell/Election_Analysis/blob/main/Resources/column_selection.png)

These modifications are simple and the output is clear. This would make it easy to extend the applicability of the code to other elections.
