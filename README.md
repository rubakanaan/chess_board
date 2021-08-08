# Chess Board


### Task:
* Define a **ChessBoard class** - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)
* should have **add_red** method that accepts a row and column as input which colors corresponding cell.
* should have **add_blue** method that accepts a row and column as input which colors corresponding cell.
* should have **render** method that displays the chess board on screen with red and blue shown in correct locations
* should have **is_under_attack** method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

### Tests:
* queens on same row should be “under attack”
* queens on same column should be “under attack”
* queens on same diagonal should be “under attack”
* queens with any other coordinates should NOT be “under attack”

### PR
* https://github.com/rubakanaan/chess_board/pull/1