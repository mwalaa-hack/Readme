# Chess Game Implementation

## Overview

This implementation provides a basic chess game with a graphical interface using `pygame`. The core functionalities include piece movement, player switching, and basic game rules.

## Chess Piece Classes

- **ChessPiece**: Base class for all chess pieces.
- **Pawn**: Moves one square forward or two squares if it's the first move.
- **Rook**: Moves horizontally or vertically.
- **Knight**: Moves in an "L" shape.
- **Bishop**: Moves diagonally.
- **Queen**: Moves both like a rook and a bishop.
- **King**: Moves one square in any direction.

## Chess Board Class

- **ChessBoard**: Initializes and sets up the board with pieces.
- **move_piece()**: Moves a piece from one position to another if valid.
- **is_checkmate()**: Placeholder function for checkmate logic.

## Chess Game Class

- **ChessGame**: Manages game state, including player turns and game progression.

## Chess GUI Class

- **ChessGUI**: Provides the graphical user interface for the chess game.
- **draw_board()**: Draws the chessboard on the screen.
- **draw_pieces()**: Draws chess pieces using image files.
- **run()**: Main game loop to handle events and update the display.

## Additional Features

- **Piece Images**: Images for pieces should be present in the working directory (`w_pawn.png`, `w_rook.png`, etc.).
- **Board Flipping**: Currently not implemented, but can be added to flip the board based on the current player.
- **Special Moves**: Castling, en passant, and pawn promotion are not implemented but could be added as extensions.

## Instructions

1. Ensure all image files for pieces are present in the working directory.
2. Run the script to start the game. The chessboard and pieces will be displayed, and you can manage game progression through the
