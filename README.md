# Football match XG analysis

In this project we are scraping football match data from understat website https://understat.com/

In this website each match is represented by a particular match-id,using that match_id we are scrapping using beautiful soup and requests.

After scraping json data we are converting json data into dictionary

The dictionary is converted into dataframe and the dataframe is saved into .csv file.

The csv file is uploaded into tableau and dashboard for each team XG is created 
![Screenshot (93)](https://user-images.githubusercontent.com/28213724/192712069-ea23f203-dbed-4925-b22f-de219ebb3828.png)
