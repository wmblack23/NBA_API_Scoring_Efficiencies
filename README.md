# NBA_API_Scoring_Efficiencies

USING LINEAR REGRESSION TO VISUALIZE THE NBA'S MOST - AND LEAST - EFFECIENT SCORERS

There are four sections to this project.  I will walk through each of them here.

1) The first section is using linear regression on a scatter-plot graph to show the correlation between SHOTS ATTEMPTED and POINT SCORED in a basketball game.  As one would expect, there is a pretty clear correlation of: the more shots a player takes, the more points they tend to score.  You can notice that as we reach the top right corner of the graph, players are outperforming the line of regression more than anywhere else.  These are the players who shoot the most, the stars of the league.  It stands to reason that as the BEST players in the NBA shoot more, they would do it at a more efficient level than the model predicts.

2) The second section of code is looking at the 5 most efficient scorers in regards to outperforming our line of regression.  The way this was calculated was by taking a player's average points per game and subtracting their expected points per game.  In other words: how much was a player outscoring their expected total of points by, given the number of shots they are taking in a game?  Again, we created a scatter-plot with a line of regression, and this time we labeled our five players on the graph.  Also, included a printed DataFrame of the 10 most effecient scorers which contains a lot more information to parse through.

3) The third section was identical to the second, just looking at the five least efficient scorers.  These are the players who score the furthest BENEATH their expected points per game based off the number of shots they attempt.

4) Lastly, I looked at the players that I believe should be shooting MORE - and who should be shooting LESS - based on the line of regression.  For me to say a player should be shooting more, they needed to score 2.0+ points per game ABOVE their expected total and take less than 14 shots per game.  This means these players were more efficient than most players while shooting less shots per game than the average of the top 100 scorers in the league.  For the guys who should shoot less, it was just the opposite.  They came at least -2.0 under their expected points per game and were firing over 14 shots per.

Of course, it isn't always as simple as saying a player should just shoot less or another should just shoot more.  A player's role is determined by the makeup of that team, and some players (Jordan Clarkson) who show up on the "SHOOT LESS" list, provide a ton of value to their team by taking and making shots, even if it is inneficient.  

As always with data, it's important to understand it tells only a part of the story.

- Michael Black
