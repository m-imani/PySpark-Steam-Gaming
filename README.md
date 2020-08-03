# PySpark-Steam-Gaming/ Working with Steam Gaming datasets in PySpark
Background: Steam is one of the largest gaming networks in the world with over 100 million active gamers. The Steam dataset covers 109 million user accounts, 196 million friendships, 3 million groups, 384 million owned games, and a collective 1 million years of playtime.
You can find out more here about the details of each dataset: https://steam.internet.byu.edu/

Data:
Small version (46 MB) : https://workable.com/nr?l=https%3A%2F%2Fstorage.googleapis.com%2Fdatatonic-steam-gaming-challenge%2Fsteam_gaming_small.zip
Large version (1.3 GB) : https://workable.com/nr?l=https%3A%2F%2Fstorage.googleapis.com%2Fdatatonic-steam-gaming-challenge%2Fsteam_gaming_large.zip

In this project, the following tasks have benn coded:
Load .csv for Player_Summaries, Game_Publishers, Game_Genres, Game_Developers, Games_1 into PySpark dataframes.
Join all `Games_` tables into one dataframe.
Count the number of games per `publisher` and per `genre`.
Find day and hour when most new accounts were created (based on Player_Summaries table).
