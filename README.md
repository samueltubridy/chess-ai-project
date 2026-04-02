# Chess AI

Developing off a chess game framework in Unity, this AI battles the player by determining the best move through the minimax algorithm. Players can select a range of difficulties from easy to hard. Bonus: Press space to get a better view of the board.

<div align="center">
<<img width="683" height="383" alt="image" src="https://github.com/user-attachments/assets/f4e5e984-ed6d-49bc-9ed7-475a37617cbc" />

  [Play the chess AI here!](https://samueltubridy.itch.io/benchmate)

<div align="left">

## How it Works

The AI minimax algorithm recursively tests board positions with a search depth depending on the selected difficulty (depth ranges from 3 to 5). Minimax was chosen because it models games where both players have equal advantage, and accordingly makes sure to alternate between maximizing White versus maximizing Black. The value of each position is determined by a comprehensive evaluation function with different criteria for opening, middle, and endgames (determined by the number of pieces remaining). These criteria include the number of moved pieces, control of the center, piece mobility, ability to castle, and avoiding draws such as move repetition and stalemate. As a result, the AI will prioritize developing pieces, advancing to the back rank, and making moves optimized for specific endgame scenarios.

## Tech Stack
- **Unity**
- **C#**
- **WebGL**

### Note: All of the code for this project is located in the /projects folder.

License: MIT
