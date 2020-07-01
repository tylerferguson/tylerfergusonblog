---
title: "What if Round 1 of the NBA Playoffs was best of 5?"
date: 2020-06-30T21:49:00
hero: /images/posts/nba-playoffs/hero.png
author:
  name: Tyler Ferguson
#   image: /assets/images/profile-image.jpg
categories:
- nba-playoffs
---

Prior to the 2002–03 NBA season the first round of the NBA Playoffs was a best of 5 format. It had been this way since the 1984 season (a year that's been coming up an awful lot lately with [a certain documentary](https://en.wikipedia.org/wiki/The_Last_Dance_(2020_TV_series)) coming out). Before 1984 the league had experimented with a few different formats. But the post-1984 format is very familiar to us all: 4 rounds in the playoffs, each round is a best of 7 series.

Except for that first round.

It always niggled me slightly. Aren't the champs of the Michael Jordan era slightly different to the champs of the Lebron James era?

_(It's a great coincidence that these format changes line up with their draft years!)_

Would anything change if we treated all first-round playoff series since 2003 as a best of 5? Are different champions crowned? Are new legacies made?

Do the Bobcats win it all?

We're going to find out!

## Results
_(If you're interested in how we get to these results using R see [Method](#method) below.)_

{{< figure src="/images/posts/nba-playoffs/1.png" caption="Playoff series where the best of 5 winner was not the same as the best of 7 winner (2003–2019)." >}}

There have only been 9 instances out of 136 since 2003 where the best of 5 winner was not the same as the best of 7 winner. But wow some of these could have had big ramifications for the rest of the playoffs.

---

## Basketball Discussion
The big stories that immediately jump out from these results are:

* T-Mac would have got out of the first round twice with the Magic and the Rockets!

* The 2003 Detroit team went all the way to the ECF (and got swept by the Nets). That could have instead been 23 year old McGrady's Magic with him averaging 31.7 ppg.
* Kobe's incredible Game 4 performance against the Suns in '06 (with 2 enormous clutch shots to force OT then win the game) would have been to close the series. Similarly, this Suns team took Dallas to 6 games in the WCF.
* In 2007, Houston would have eliminated the Jazz team that made it all the way to the WCF and lost to the eventual champion Spurs in 5. T-Mac's Rockets may have had a chance even though his scoring output had dropped since Yao was picking up some of the slack.
* The 2014 playoffs would have looked completely different. Three of the best of 5 victors were different from the best of 7 victors in our reality.

### Potential Effects on the Rest of The Playoffs
Each of these alternate winners causes a ripple effect through the rest of The Playoffs. It affects not only round 2 matchups, but potentially The Finals series itself. Can we assess the impact of these Round 1 series following a best of 5 format?

I had initially intended to programmatically look up matchup data for the season for each upset and work out the potential new champion. Since there are so few examples I just looked it up by hand.

For each matchup that never occurred, I have used their season series to help predict the outcome.

1. **2003 R1: ORL advance over DET.**

    **R2: ORL-PHI.** The '03 Magic went 2–2 in the season series against the Sixers so it's not immediately clear who would have made the ECF.

    **ECF: ORL-NJN.** If they had won and played the Nets in the ECF then they had again split the season matchups 2–2. This seems like another toss-up to me. 

    **Finals: ORL-SAS.** We could have had T-Mac and the Magic in The Finals against the Spurs. The Magic had dropped both games against the Spurs that season 0–2. The Spurs and MVP Tim Duncan still take this series but T-Mac would be freed of the idea that he was unable to get it done in The Playoffs.
    
    **Champions: SAS (Reality: SAS)**

2. **2006 R1: LAL advance over PHX.**

    **R2: LAL-LAC.** In the season they went 2–2. But Kobe was incredible this year with the highest scoring output of his career and the 81 point game. The playoffs were no different - the man was absolutely unconscious from the mid-range and 3 with a 59% TS% and 40% 3P%. I see the Lakers taking this series, especially with the momentum of Game 4 against the Suns.

    **WCF: LAL-DAL.** The Lakers took the season series here 2–1. This surprised me. This Lakers team was truly trash and I would expect Dallas to make fairly light work of them. But maybe, just maybe, they could have gone to The Finals against Miami.

    **Finals: LAL-MIA.** Picture the scene. Young D. Wade matching up against Kobe. The Shaq vs. Kobe narrative. We are just two years removed from Shaq and Kobe's last tumultuous season together. This would be a bloodbath. The season series was split 1–1. This is anyone's finals. But with Kobe and Shaq having their egos on the line like this it would be a hell of a watch. If the Lakers manage to squeak past the Mavs, I'm very tempted to give them the edge here.

    **Champions: MIA / LAL (Reality: MIA)**

3. **2007 R1: HOU advance over UTA.**
    
    **R2: HOU-GSW.** This is the "We Believe" Warriors who just dispatched a terrific Mavs team with MVP Dirk Nowitzki. Houston also lost the season series 2–1. This is likely the end of the road for the Rockets again. 

    **WCF: HOU-SAS.** If Houston manages to advance they meet San Antonio who they matched up with during the season at 2–2. But I don't think they are dismantling the eventual champions with their fresh-faced big three.

    **Finals: HOU-CLE.** On the off-chance they do make it to The Finals they meet Lebron and the Cavs. They split the season series 1–1. I don't think the Rockets pull off all three of these upsets.

    **Champions: SAS (Reality: SAS)**

4. **2010 R1: MIL advance over ATL.**

    **R2: MIL-ORL.** The Bucks have three L's in the three regular-season games against the Magic. I don't think Bogut contains 2010 Dwight Howard. Sorry Bucks. At least the future is bright now!

    **Champions: LAL (Reality: LAL)**

5. **2014 R1: ATL advance over IND.**

    **R2: ATL-WAS.** The Hawks have a 1–3 record against Washington with their only win coming in OT. They lose. But there's more to come for 2014!

6. **2014 R1: TOR advance over BKN.**

    **R2: TOR-MIA.** Toronto went 0–4 against the Heatles in the regular season. Death, taxes, Spurs making The Playoffs, and Lebronto. Raptors lose without a shadow of a doubt. There is one last hope for change in 2014…

7. **2014 R1: MEM advance over OKC.**
    **R2: MEM-LAC.** The Grit and Grind Grizzlies took the season series 2–1. Lob city had trouble making it happen in the playoffs. The Grizz advance.

    **WCF: MEM-SAS.** If they advance to the next round they meet the eventual champion Spurs who they lost all 4 games to that season. This was a tough Memphis team but no one was stopping the Spurs in 2014. [That San Antonio team was one of the greatest teams to ever play the game](https://www.youtube.com/watch?v=T3y7cWmoBCI).

    **Champions: SAS (Reality: SAS)**

8. **2015 R1: SAS advance over LAC.**

    **R2: SAS-HOU.** The defending champion 2015 Spurs meet the Rockets who they beat 3–1 in the regular season. They take the series comfortably as Howard struggles against Duncan. 
    
    **WCF: SAS-GSW.** The Spurs meet the eventual champion Golden State Warriors in the WCF. The Spurs took the season series 2–1 and could easily upset the 1 seed. If that were to happen (and that's a big if with Steph and Klay breaking out big time these playoffs) they meet Lebron and the Cavs in the finals.

    **Finals: SAS-CLE.** This would be the third team that the Spurs would have met in the finals with a player named Lebron James. They had split the season series 1–1. This series could have been wild with it in some sense being a rematch of the previous year. Timmy might be looking at yet another ring. Weirdly, this matchup is probably better for Lebron than GSW that year as well. Would have been fun to watch that's for sure. If the Spurs are good enough to eliminate GSW then they probably take these Finals as well, but it is very difficult to call.

    **Champions: SAS / CLE / GSW (Reality: GSW)**

9. **2016 R1: CHA advance over MIA.**

    **R2: CHA-TOR.** The season series was 1–2 in favour of Toronto with the only win for Charlotte coming in OT. The Raptors probably eliminate the Hornets here. 

    **ECF: CHA-CLE.** But if Charlotte survives then they meet Lebron and the Cavs in the ECF. They lost the season series 1–3 (the famous game where the Hornets beat a Lebron team but Kemba Walker retains his streak of losses against Lebron by missing the game). Given that Kemba would probably play in the series, this is a guaranteed sweep. 4–0. Cavs win.

    **Champions: CLE (Reality: CLE)**

---

## Conclusion
Most of the time the right team still wins. Or as Rasheed Wallace would put it, "Ball don't lie". But some of these outcomes do have the potential to impact who wins the championship.

I think it's interesting to consider how much legacy and perception of athletes are affected by small format changes like this. It's a long shot but Kobe could have one more ring - 6 in total - putting him in the vaunted company of Jordan. Duncan has a much better chance of getting another and taking him up to 6. Lebron too could have one more which would help his perceived struggles in the Finals.

The keen-eyed amongst you will have noticed that this whole question is actually the same as "which teams have come back from a 3–1 or 3–2 series deficit in Round 1?". But it's much more fun to frame the question in terms of the format change - it allows for some much more natural speculation!

The reality is that sports balance on a knife-edge. The tiniest detail can flip the whole script. That's what keeps us all coming back for more. One 0.4 second shot, push off, or 3–1 comeback can be the difference between one legacy born and another lost.

And sometimes, it can come down to a decision made in a board room to change the format from best of 5 to best of 7.

---

## Method
### Getting Data
I use the [nbastatR](http://asbcllc.com/nbastatR/) package which I can thoroughly recommend for anyone that uses R (or just needs a CSV) and wants to programmatically fetch NBA data of all different flavours.

The NBA first moved to a best of 7 format for the first round in the 2003 Playoffs. We need all playoff series and game results since then.

{{< gist tylerferguson a6f0e9950fe62eac6353a77f72f5fe39 >}}

The `game_logs` function from nbastatR scrapes all games for all teams in every playoffs since 2003 from Basketball-Reference.

Here's a preview of that `games` table:

    ## # A tibble: 6 x 47
    ##   yearSeason slugSeason slugLeague typeSeason dateGame   idGame numberGameTeamS…
    ##        <int> <chr>      <chr>      <chr>      <date>      <dbl>            <int>
    ## 1       2003 2002-03    NBA        Playoffs   2003-04-19 4.02e7                1
    ## 2       2003 2002-03    NBA        Playoffs   2003-04-19 4.02e7                1
    ## 3       2003 2002-03    NBA        Playoffs   2003-04-19 4.02e7                1
    ## 4       2003 2002-03    NBA        Playoffs   2003-04-19 4.02e7                1
    ## 5       2003 2002-03    NBA        Playoffs   2003-04-19 4.02e7                1
    ## 6       2003 2002-03    NBA        Playoffs   2003-04-19 4.02e7                1
    ## # … with 40 more variables: nameTeam <chr>, idTeam <dbl>, isB2B <lgl>,
    ## #   isB2BFirst <lgl>, isB2BSecond <lgl>, locationGame <chr>, slugMatchup <chr>,
    ## #   slugTeam <chr>, countDaysRestTeam <dbl>, countDaysNextGameTeam <dbl>,
    ## #   slugOpponent <chr>, slugTeamWinner <chr>, slugTeamLoser <chr>,
    ## #   outcomeGame <chr>, isWin <lgl>, fgmTeam <dbl>, fgaTeam <dbl>,
    ## #   pctFGTeam <dbl>, fg3mTeam <dbl>, fg3aTeam <dbl>, pctFG3Team <dbl>,
    ## #   pctFTTeam <dbl>, hasVideo <lgl>, fg2mTeam <dbl>, fg2aTeam <dbl>,
    ## #   pctFG2Team <dbl>, minutesTeam <dbl>, ftmTeam <dbl>, ftaTeam <dbl>,
    ## #   orebTeam <dbl>, drebTeam <dbl>, trebTeam <dbl>, astTeam <dbl>,
    ## #   stlTeam <dbl>, blkTeam <dbl>, tovTeam <dbl>, pfTeam <dbl>, ptsTeam <dbl>,
    ## #   plusminusTeam <dbl>, urlTeamSeasonLogo <chr>

There's a lot of columns there and it's not that pretty to look at so let's reduce it down to the parts we'll need and have another peek at the first few rows:

{{< figure src="/images/posts/nba-playoffs/2.png" caption="First 6 rows of games table" >}}

### Identifying Playoff Rounds, Series and Games
The first thing to notice is how the `idGame` isn't unique for each game: the 1st and 2nd row share the same value, 3rd and 4th, etc. This is because the games table has all game logs from both the home and away perspective so all games are duplicated once. The first two rows are the same game between Sacramento and Utah, the next two the same game between Dallas and Portland, etc. We'll consider all games from just the home perspective to get rid of those duplicates.

We also need a way to identify which games belong to a series and to tell which of those series are in the first round. I was thinking about a few different ways of doing this when I just happened to notice that the 'idGame' actually has some structure to it which we can take advantage of. The variables we can create are:

* `Game`: the game number of the playoff series. This is the last digit of `idGame` e.g. 1 indicates Game 1, 7 indicates Game 7 etc.
* `Matchup`: the particular series / matchup this game belongs to in the playoff bracket. This is the second to last digit of `idGame` with 1 added to it e.g. 1 is the matchup between 1st and 8th seed in the East, 2 is 2nd and 7th seed, 5 is 1st and 8th seed in the West etc.
* `Round`: the round of The Playoffs this game belongs to. This is the digit before the `Matchup` digit (third to last) in `idGame` e.g. 1 is Round 1, 2 is Round 2, 3 is W/ECF and 4 is finals.

Finally, we make use of [assertr](https://docs.ropensci.org/assertr/) to make sure the assumptions and variables we've created are valid.

{{< gist tylerferguson 92a6feb663f981074c6a986ab3b10765 >}}

{{< figure src="/images/posts/nba-playoffs/3.png" caption="First 6 rows of home_games table with the three new variables Game, Matchup and Round" >}}

### Finding Best of 5 Winners in Round 1
There's one more thing we need before being able to work out who won the best of 5 and that is a count of cumulative wins for each game in a series. We do this by sorting all games ascending by date, then grouping them into the season, round, series matchup, and winner.

For a given series this results in two groups: the group of games where Team A won, and the group of games where Team B won. The number of cumulative wins is just the row number in each of those groups, e.g. the first row in group A is the first game that Team A has won, the second row the second game won and so on.

{{< gist tylerferguson e74be7ccfbed7cb82ab2b357c99a35bb >}}

{{< figure src="/images/posts/nba-playoffs/4.png" caption="First 6 rows of home_games table with cumulative Wins variable." >}}

We are now at our final step. In order to find the teams that won Round 1 in a best of 5 format we need to filter down to Round 1 games and sort ascending by date, then consider each series and summarise the original `BestOf7Winner` as the team that won 4 games and the `BestOf5Winner` as the team that was the first to win 3 games.

{{< gist tylerferguson c5be3abd698b9ecd1b30d5830d568f40 >}}

{{< figure src="/images/posts/nba-playoffs/5.png" caption="First 6 rows of round1_winners table. Note the discrepancy on the very first row between the two winners." >}}

Straight away, by sheer coincidence, we can see an example where there would have been a difference! The Round 1 series between Detroit and Orlando in 2003. Just one year before and Orlando would have walked away from this series with the win.

To follow a basketball discussion go to the [Results](#results) section.

_([This post was initially shared on medium.com](https://medium.com/@tyler.ferguson/what-if-round-1-of-the-nba-playoffs-was-best-of-5-7f91168c6eee).  I'll write a blog post soon on why I'm moving existing and future content away from Medium.)_
