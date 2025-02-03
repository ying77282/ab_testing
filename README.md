# Part 1: Project Background

Cookie Cats is a popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" -style puzzle game where the player must connect tiles of the same color to clear the board and win the level.

## Problem Statement 

1. As player progress through the levels of game, they will occasionally encounter gates that force them to wait a non-trival amount of time or make in-app purchase to progress.
2. In-app purchase serves as the purpose of giving players an enforced break from playing the game, resulting in that the player's enjoyment of the game being increased and prolonged.

## Purpose

1. Initially the first gate was placed at lvl 30. We are going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40.


# Part 2: Data

## Column of Data:

1. userid - unique number that identifies each player
2. version - whether the player was put in control group (gate30 -  gate at lvl 30) or test group (gate40 - gate at lvl 40)
3. sum_gamerounds - the number of game rounds played by the players during the first week after installation
4. retention_1 - did the player come back and play 1 day after installing
5. retention_7 - did the player come back and play 7 days after installing

   

