# League-of-Legends-Diamond-Ranked-Games-first-10-min-

## About Dataset

League of Legends is a MOBA (multiplayer online battle arena) where 2 teams (blue and red) face off. 

This dataset contains the first 10min stats of 9879 ranked games from a high ELO. In other words, ordinary players will not be able to play in such a high-ranking game. To an extent, it reduced the deviation from this analysis. 

The goal in the game is to kill minions and opponent champions to gain money for buying better equipments. Whichever team take down the enemy homebase(Nexus) win the game. Either win or lose the game, there's no "tie game".

There are 19 features per team (38 in total) collected after 10 min in-game. This includes kills, deaths, gold, experience, level etc. I will be using part of the data to discover some insight from our EDA.

#### Player distribution in rankings
Iron:  1.7 % <br>
Bronze: 18 % <br>
Silver: 36 % <br>
Gold: 29 % <br>
Platinum: 12 % <br>
**Diamond: 1.6 %** <br>
Master: 0.21 % <br>
Grandmaster: 0.024 % <br>
Challenger: 0.010 % <br>

Data Resource: https://dotesports.com/league-of-legends/news/league-of-legends-ranking-system-explained-17171

### EDA Questions to  be answered

In this notebook, I will be using blue team as a sample to dig into this dataset.

1. What's the winning rate for the each team in this 9879 ranked games dataset?
2. The impact of first blood on winning
3. The impact of total minions killed on winning
4. The impact of death on winning
5. The Kills (Blue & Red team comparison)

LETS GO!
