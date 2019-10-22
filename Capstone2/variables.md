# Variables

The following is a reference of the variables within this project used for exploratory analysis and modeling.

| Variable | Description |
| -------- | ----------- |
| `date` | The date on which the football game was played |
| `Opponent` | The player's opponent within a game |
| `gameId` | A key variable representing a played game |
| `Name` | The name of a player |
| `Team` | The team a player plays for |
| `season` | The NFL season in which this instance occured |
| `Week` | The NFL week in which this instance occured |
| `homeAway` | Tells whether the player was the home team or away team |
| `surface` | Tells whether the player was playing on a turf or grass field |
| `roof` | Tells whether the player was playing in a dome or outdoors |
| `PassingCompletions` | A quarterback's total passes completed within the game |
| `PassingAttempts` | A quarterback's total passes attempted within the game |
| `PassingCompletionPercentage` | The percentage of passes a quarteback completed within the game |
| `PassingYards` | The number of yards a quarterback passed for in the game |
| `PassingYardsPerAttempt` | The average number of yards a quarterback threw for per attempt |
| `avgPYA` | The average number of passing yards the opposing defense allows per game |
| `PassingTouchdowns` | The number of passing touchdowns a quarterback threw for |
| `avgPassingTouchdowns7` | The average number of touchdown a quarterbacks throws for over his most recent 7 games |
| `PassingTouchdownsPerAttempt` | The number of passing touchdowns per attempt a quarterback throws for |
| `PassingInterceptions` | The total number of interceptions a quarterback throws for within the game |
| `PassingRating` | A metric the measures a quarterback's efficiency within the game |
| `avgPassingRating7` | The average passing rating for the quarterback over his most recent 7 games |
| `RushingAttempts` | The number of rushing attempts a quarterback has within the game |
| `RushingYards` | The number of rushing yards a quarterback has within the game |
| `RushingYardsPerAttempt` | The number of rushing yards per attempt a quarterback has within the game |
| `RushingTouchdowns` | The number of rushing touchdowns a quarterback has within the game |
| `avgPf` | The average number of points scored for a quarterback's team before the game begins |
| `avgOvr_x` | The average overall grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `avgOff` | The average offensive grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `avgPass` | The average passing grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `avgPblk` | The average pass blocking grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `avgRecv` | The average receiving grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `avgRun` | The average run grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `avgRblk` | The average run blocking grade of a quarterback's team over the last 7 games using ProFootballFocus grades |
| `totalDvoa_x` | A metric from footballoutsiders.com that measures how strong a team is overall |
| `offDvoa` | A metric from footballoutsiders.com that measures how strong a team is offensively |
| `stDvoa` | A metric from footballoutsiders.com that measures how strong a team's special teams unit is |
| `pa` | The total number of points a quarterback's team allowed to the opponent |
| `avgPa` | The average number of points the quarterback's team allows per game |
| `avgOvr_y` | The average overall grade of a quarterback's opponent's team over the last 7 games using ProFootballFocus grades |
| `avgDef` | The average defensive grade of a quarterback's opponent's team over the last 7 games using ProFootballFocus grades |
| `avgRdef` | The average run defense grade of a quarterback's opponent's team over the last 7 games using ProFootballFocus grades |
| `avgPrsh` | The average pass rush grade of a quarterback's opponent's team over the last 7 games using ProFootballFocus grades |
| `avgCov` | The average coverage grade of a quarterback's opponent's team over the last 7 games using ProFootballFocus grades |
| `totalDvoa_y` | A measure of the opposing team's overall strength via footballoutsiders.com |
| `defDvoa` | A measure of the opposing team's defensive strength via footballoutsiders.com |
| `ptsMatchup` | A metric that accounts for the amount of points a team scores and the amount of points the opposing defense allows |
| `offMatchup` | A metric that accounts for the offensive strength of the team and the defensive strength of the opponent |
| `ovrMatchup` | A metric that accounts for the overall strength of the team and the overall strength of the opponent |
| `passMatchup` | A metric that accounts for the passing strength of the team and the coverage strength of the opponent |
| `pblkMatchup` | A metric that accounts for the pass blocking strength of the team and the pash rushing strength of the opponent |
| `runMatchup` | A metric that accounts for the rushing strength of the team and the run defense strength of the opponent  |
| `offDvoaMatchup` | A metric that accounts for the offensive dvoa of the team and the defensive dvoa of the opponent |
| `totalDvoaMatchup` | A metric that accounts for the total dvoa of the team and the total dvoa of the opponent |
| `pf` | The total number of points a quarterback's team scored within the game |
| `spread` | How many points a team is favored to win the game by, multiplied by -1 |
| `total` | The total number of points that sports books project to be scored in the game between both teams combined|
| `impliedTotal` | A function of the spread and total that projects how many points an individual team will score in the game |
| `result` | Tells whether a game finishes with more (over) or less (under) points than the 'total' variable |
| `winLose` | Tells whether a quarterback's team won or lost the game |
| `FantasyPointsPerGame7` | A quarterback's average fantasy points scored per game over his most recent 7 performances |
| `oTot` | A measure of how effective a team was offensively within the game via pro-football-reference |
| `oPass` | A measure of how effective a team's passing offense was within the game via pro-football-reference |
| `oRush` | A measure of how effective a team's rushing offense was within the game via pro-football-reference |
| `oTov` | A measure of how effective a team's rushing offense was within the game via pro-football-reference |
| `firstDowns` | The total number of first downs achieved for the team within the game |
| `totYds` | The total amount of yards ammased for the team within the game |
| `to` | The total number of team turnovers within the game |
| `timesSacked` | The amount of times the quarterback was sacked |
| `yardsLostOnSacks` | The amount of yards lost on sacks within the game |
| `totalSeconds` | The number of seconds the quarterback's team had the bal throughout the game |
| `lateDownConv` | The number of 3rd and 4th down conversions that were successful for the team |
| `lateDownAtt` | The total number of 3rd and 4th down attempts |
| `totExpAvg` | Avg. of totExp over a team's last seven games |
| `oTotAvg` | Avg. of oTot over a team's last seven games |
| `oPassAvg` | Avg. of oPass over a team's last seven games  |
| `oRushAvg` | Avg. of oRush over a team's last seven games  |
| `oTovAvg` | Avg. of oTov over a team's last seven games  |
| `firstDownsAvg` | A team's average number of first downs per game |
| `totYdsAvg` | A team's total yards per game over the past seven games |
| `toAvg` | A team's turnovers per game over the past seven games |
| `passCompAvg` | Avg. number of completed passes over a team's last seven games |
| `passAttAvg` | Avg. number of completed attempted over a team's last seven games |
| `passYdsAvg` | Avg. number of passing yards over a team's last seven games |
| `passTdsAvg` | Avg. number of passing touchdowns thrown over a team's last seven games |
| `intsAvg` | Avg. number of interceptions thrown over a team's last seven games |
| `timesSackedAvg` | Avg. number of times sacked over a team's last seven games |
| `totalSecondsAvg` | The avg. amount of seconds a team possesses the ball |
| `lateDownConvAvg` | Avg. late down conversions per game |
| `lateDownAttAvg` | Avg. late down attempts per game |
| `defPassingYardsAllowed7` | Opposing defense's avg passing yards allowed over the past seven games |
| `defOtotAllowed7` | Opposing defense's avg passing yards allowed over the past seven games |
| `defOpassAllowed7` | Opposing defense's avg oPass allowed over the past seven games |
| `defFirstDownsAllowed7` | Opposing defense's avg first downs allowed over the past seven games |
| `defPassTdsAllowed7` | Opposing defense's avg passingtouchdowns allowed over the past seven games |
| `defPassingRatingAllowed7` | Opposing defense's avg passer reating allowed over the past seven games |
| `defFantasyPointsAllowed7` | Opposing defense's avg fantasy points allowed to quarterbacks over the past seven games |
| `defPYAallowed7` | Opposing defense's avg passing yards allowed over the past seven games |
| `yardsMatchup` | A metric that accounts for a team's avg total yards and the opposing defense's total yards allowed |
| `oTotMatchup` | A metric that accounts for a team's avg oTot and the opposing defense's oTot allowed |
| `oPassMatchup` | A metric that accounts for a team's avg oPass and the opposing defense's oPass allowed |
| `firstDownMatchup` | A metric that accounts for a team's avg first downs and the opposing defense's first downs allowed |
| `passTdMatchup` | A metric that accounts for a team's avg passing touchdowns and the opposing defense's passing touchdowns allowed |
| `passingRatingMatchup` | A metric that accounts for a team's avg passer rating and the opposing defense's passer rating allowed |
| `fptsMatchup` | A metric that accounts for a quarterack's avg fantasy points and the opposing defense's avg fantasy points allowed |
| `PYAMatchup` | A metric that accounts for a team's avg passing yards and the opposing defense's passing yards allowed |
| `FantasyPointsFanDuel` | Target Variable. Hwo many FanDuel points a quarterback scored |
