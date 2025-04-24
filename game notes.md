# Identify the State variables for Connect-Four:

## board
Array of Arrays, where the nested arrays will represent the columns.

Values that the elements contain:
- 1/-1 -> player
- null →> cell is empty

## winner

Values:
- null →> no winner or tie, game is in progress
- 1/-1 →> the player that won
- 'Tie' →> the game is tied

## turn

Values:
- 1/-1 →> which player