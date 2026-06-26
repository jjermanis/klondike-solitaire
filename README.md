# klondike-solitaire
Playing Klondike Solitaire


## Overview
Playing a specific version of Klondike Solitarie. It is the variation of interest within my family.
There is a low-frequency critical defect in the game. It has been seen once that cards get removed entirely from a game; the total number of cards in the game drops below 52. The root cause has not been identified. It has been seen and confirmed only once.


## Direction
This is a standard Klondike Solitaire game. It starts with 7 columns of different sizes. The goal is to completely fill the 4 foundations. There is a stock of cards to draw from.
The options lean toward simple: you draw one card at a time, you can go through that deck as many times as you want.
You can move cards either by click-and-drag or clicking on them. If you click, it will make a legal move if it exists. It will try the foundation first, and there is no move there, it will try columns, from left to right.
There is an Undo button on the lower-left if you have made a mistake, or if you want to try a different move. It can be used to rewind all the way to the beginning.
There is a New Game button in the lower-center if you'd like to start another game.


## Details
Truly, the root cause of the missig cards is unknown. Feel free to share info with me if it happens to you.


## Mobile
This game works well on a tablet. It works best if held in portrait orientation. It will work in landscape orientation, but it is slow. The UI is simple: tap the screen instead of click.

This game is not sized for a mobile phone.


## From Release #1 (Build 01.12 on 6/20/26)

* Implements the base version of the game.

