# Tic Tac Toe AI

A command line tic tac toe game implemented in python in which the computer never loses.
The computer makes it moves with the help of a decision making algorithm called minimax.

## How to play:
1. Clone the repository
2. Run game.py using python interpreter

## To switch who plays first:
In game.py go to the bottom of the file and change it to the following:
```python
if __name__ == "__main__":
    x_player = HumanPlayer('X')
    o_player = GeniusComputerPlayer('O')
    t = TicTacToe()
    play(t, x_player, o_player, print_game=True)
```
