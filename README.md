# [BETA TESTING] Do RDR2 Challenges in Any Order You Want LML Mod
This is a dump of the files edited to allow you to progress all the avaiable challenges in the game right from the start.
# WARNING /BACKUP YOUR SAVEDGAME
Due to the way i created this mod by creating each Challenge ID for every rank, 
that means that the **game resets your current challenges progress** at the moment the game loads the new challenges IDs,
but dont worry, the game wont keep resetting the progress afterwards.
so please if you just want to test the mod, remember to **BACKUP YOUR SAVEDGAME**

![image](https://user-images.githubusercontent.com/62562208/162847227-d1132dae-8f92-4cb4-9cb3-6e9cb21cf782.png)

## Bugs found
+ The game dont add to the progress, objectives that have scoreSource type="StatsGoalScoreSourceScript" as part of their score system. The fix i found for this was to set its parent challenge name/id to its original name (case/scenario: MASTER HUNTER RANK 2), but unfortunally the game have other ranks with this type of score that belong in the same challenge, so a fix for this isnt doable for this other cases now (Need help from .ASI programmers).
  ¨Ranks possible affected by this type of score, but not tested yet: GAMBLER RANK 4 (poker), GAMBLER RANK 6(blackjack), GAMBLER RANK 7 (fivefinger)
