Bug Descriptions:

Memory Puzzle
memorypuzzle_buggy1.py - Graphics are messed up.
memorypuzzle_buggy2.py - IndexError: list index out of range
memorypuzzle_buggy3.py - Box highlight lags
memorypuzzle_buggy4.py - icons don't show up
memorypuzzle_buggy5.py - NameError: global name 'getRandomizedBoard' is not defined
memorypuzzle_buggy6.py - Box hide/reveal animation is very choppy.
memorypuzzle_buggy7.py - No gaps are showing up on the board.
memorypuzzle_buggy8.py - TypeError: 'NoneType' object is not iterable

Slide Puzzle
slidepuzzle_buggy1.py - Clicking reset crashes the game: "NameError: global name 'resetAnimation' is not defined"
slidepuzzle_buggy2.py - SyntaxError: EOL while scanning string literal
slidepuzzle_buggy3.py - Sliding down causes the tile to move down-right.
slidepuzzle_buggy4.py - Clicking Solve twice causes it to make several extra moves the second time.
slidepuzzle_buggy5.py - Game won't start: "pygame.error: font not initialized"
slidepuzzle_buggy6.py - SyntaxError: invalid syntax
slidepuzzle_buggy7.py - Clicking "New Game" causes "IndexError: string index out of range"
slidepuzzle_buggy8.py - Puzzle starts off with tiles shifted off by 1 space, and there are two blank spots.


Simulate
simulate_buggy1.py - Game crashes for no reason - "NameError: global name 'BRIGHTYELOW' is not defined"
simulate_buggy2.py - Blue button overlaps the yellow button.
simulate_buggy3.py - Pressing the "W" key doesn't work.
simulate_buggy4.py - Game crashes - "NameError: global name 'BEEP4' is not defined"
simulate_buggy5.py - Window appears too tall.
simulate_buggy6.py - Yellow button doesn't flash.
simulate_buggy7.py - Buttons don't flash.
simulate_buggy8.py - Game doesn't run - "IndentationError: unindent does not match any outer indentation level"




Wormy
wormy_buggy1.py - Worm sometimes does not appear on the board, and "Game Over" appears a second or two later.
wormy_buggy2.py - Worm keeps growing.
wormy_buggy3.py - Pressing down makes the worm go up.
wormy_buggy4.py - Worm can go off the left and right edges.
wormy_buggy5.py - Program hangs with a black screen when it first starts.
wormy_buggy6.py - NameError: global name 'DOWN' is not defined
wormy_buggy7.py - An invisible vertical wall near the middle causes the player to game over.
wormy_buggy8.py - Player can't change direction, and pressing the left arrow key causes a game over.


Tetromino
tetromino_buggy1.py - Music keeps going after Game Over
tetromino_buggy2.py - Game crashes in the middle for no reason - "IndexError: string index out of range"
tetromino_buggy3.py - "Press a key to play." text isn't in the center.
tetromino_buggy4.py - Game doesn't run. "NameError: name 'Z_SHAPE_TEMPLATE' is not defined"
tetromino_buggy5.py - Game crashes when a piece lands ("IndexError: list assignment index out of range"), or pieces change shape after landing.
tetromino_buggy6.py - Game crashes when a piece lands ("IndexError: list index out of range")
tetromino_buggy7.py - Complete lines won't clear.
tetromino_buggy8.py - Game freezes as soon as the player makes a complete line.

Squirrel
squirrel_buggy1.py - Game doesn't run - "KeyError: 'widht'"
squirrel_buggy2.py - Game never resets after the first game over.
squirrel_buggy3.py - First hit causes two damage, and then the player doesn't take damage afterwards.
squirrel_buggy4.py - Squirrel disappears after moving down.
squirrel_buggy5.py - Game doesn't run - "NameError: global name 'L_SQUIR_IMG' is not defined"
squirrel_buggy6.py - Game doesn't run - "TypeError: 'dict' object cannot be interpreted as an integer"
squirrel_buggy7.py - No squirrels show up.
squirrel_buggy8.py - When you win the game, "(Press "r" to restart.)" text doesn't appear in the center.

Star Pusher
starpusher_buggy1.py - Error when you first try to move: "TypeError: makeMove() takes exactly 2 positional arguments (3 given)"
starpusher_buggy2.py - Crashes when you solve a level: "KeyError: 'solve'"
starpusher_buggy3.py - Level is solved as soon as you make your first move.
starpusher_buggy4.py - Background is black on the start screen.
starpusher_buggy5.py - Game crashes at start of first level: "AssertionError: Level 1 (around line 35) in starPusherLevels.txt is missing a "@" or "+" to mark the start point." (But the map file is fine.)
starpusher_buggy6.py - Game crashes at start of the first level: "IndexError: list index out of range"
starpusher_buggy7.py - Game crashes at start of the first level: "AttributeError: event member not defined"
starpusher_buggy8.py - Map appears super skinny.

Flippy
flippy_buggy1.py - Black bar appears at the bottom of the screen.
flippy_buggy2.py - Game crashes on computer's turn - "TypeError: 'NoneType' object is not iterable"
flippy_buggy3.py - Board appears on right side of the screen.
flippy_buggy4.py - Computer wins at the start of the game with several pieces on the board.
flippy_buggy5.py - Game crashes on player's move - "TypeError: 'bool' object is not subscriptable"
flippy_buggy6.py - Game instantly ends as a tie.
flippy_buggy7.py - Game instantly ends as a tie.
flippy_buggy8.py - Player always goes first.

Ink Spill
inkspill_buggy1.py - Logo doesn't appear in the upper right
inkspill_buggy2.py - Can't select small board on settings page.
inkspill_buggy3.py - Player wins after first move.
inkspill_buggy4.py - Game doesn't run - "IndexError: list index out of range"
inkspill_buggy5.py - Game doesn't run - "NameError: name 'random' is not defined"
inkspill_buggy6.py - First move is always red, and then the player can't make any more moves.
inkspill_buggy7.py - Game is just a black screen.
inkspill_buggy8.py - Background is black.

Four in a Row
fourinarow_buggy1.py - Game won't run - "IndexError: list index out of range"
fourinarow_buggy2.py - Game won't run - "NameError: global name 'COMPUTER' is not defined"
fourinarow_buggy3.py - Game won't run - TypeError: 'NoneType' object is not iterable
fourinarow_buggy4.py - Computer will never move on the rightmost column.
fourinarow_buggy5.py - If player's first move is not over the board, then the game crashes: "UnboundLocalError: local variable 'column' referenced before assignment"
fourinarow_buggy6.py - Game won't run - "IndexError: list index out of range"
fourinarow_buggy7.py - When dropping a token on a tall stack, the token appears to drop past the top token on the stack.
fourinarow_buggy8.py - Computer's token seems to fly off the screen, and then the program hangs.

Gemgem
gemgem_buggy1.py - Game doesn't run, and doesn't display any error message.
gemgem_buggy2.py - Game crashes at the start. "TypeError: drawBoard() takes exactly 1 positional argument (0 given)"
gemgem_buggy3.py - Game won't run - "pygame.error: Couldn't open gem8.png"
gemgem_buggy4.py - Game won't run - "TypeError: list indices must be integers, not str"
gemgem_buggy5.py - Matching gems gives a negative score, and moving a gem to make a match in a horizontal line doesn't cause two of the gems to disappear
gemgem_buggy6.py - First match causes other gems to disappear.
gemgem_buggy7.py - Board has missing rows of gems.
gemgem_buggy8.py - Game doesn't run - "NameError: global name 'BOARDRECTS' is not defined"