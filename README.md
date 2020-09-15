# How do playoffs affect free throws?

This repository contains all of the steps in the analysis of the question above. This includes  a folder containing all the data, a notebook where all the data was cleaned and analyzed, an article, and a presentation. Below, I will go into what you can expect from each of these.

### Data

 The data folder contains two .csv files. The first one named `free_throws.csv` contains data on every free throw shots taken from 2006-2015 in the NBA. This data has 618,019 rows and 13 columns. It contains what season the shot was from, the player who shot it, the period, whether it was made or missed, whether it was playoffs or regular season, and a few more columns of data.

The second .csv files is called `cleaned_data.csv`. This data set contains the data that was used for our analysis. The shape of this DataFrame is 618,019 by 5. The five columns we used were `period`, `player`, `playoffs`, `shot_made`, and `season_start`. All of these were essential to our analysis. Finally, there was no missing data so no rows had to be dropped.

### Notebooks

Our notebook contains the code to clean the data, which is pretty straightforward. We then went into analysis. Our analysis consisted of first seperating the DataFrame into multiple other DataFrames. These new DataFrames were based on it being playoffs or regular season and if the shot was made or not. We then created a histogram using Matplotlib. The histogram shows the percentage by player of the shots made for the regular season and the playoffs.

Our next analysis was on whether seasons showed trends in the percentage for playoffs or regular season free throw percentage. We made a few bar graphs where we found that in 2011 the lockout caused a lot less free throw shots to be taken. Although this was true, the percentage of made to missed free throw shots was identical to the other seasons. Furthermore, we developed a line plot that gave us more insight into the percentage per season. The line plot showed us that there isn't any trend between playoffs and percentage of shots made. We did find that in 2014 though, the playoff percentage dropped drastically. We found this was due to an unsual amount of teams shooting in the 60-70% range during those playoffs.

Our last analysis was the percentage per quarter. Here we found that when you normalize a graph of shots taken per quarter you find that the playoff and regular season graph is identical. This helped bring us to the conclusion that no matter if it is the playoffs or the regular season the flow of the game is the same. Finally, we finished our analysis with another line plot showing the change in the percentage of made shots per quarter. Here we saw that the playoffs lacked behind regular season until overtime where it jumps over 4%. This was the only evidence of the playoffs showing any effect on free throw shooting percentage, but we cannot solely say playoffs are the factor since it being overtime could be what makes people shoot better.

Our final analysis was that playoffs do not affect free throw percentage since players don't let the pressure get to them.

### Article

This folder contains an article on Linkedin about our entire analysis.

### Presentation

This folder contains a presentation over the same material the article contains. The visuals are better explained here and there are more uses of charts of data.
