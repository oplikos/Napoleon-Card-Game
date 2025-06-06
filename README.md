# Napoleon-Card-Game  

Distribution rules you want:

We have 3 columns: Left, Middle, Right.

Cards are dealt row by row, left & right columns only (no cards initially go to the middle except Aces).

First card → Left column, row 1

Second card → Right column, row 1

Third card → Left column, row 2

Fourth card → Right column, row 2

… continue alternating like this until 5 rows are filled.

Whenever an Ace appears during dealing:

Instead of putting it in the left or right column for that row, place the Ace in the middle column for that row.

Then, the card that would have been placed in the spot where the Ace went is placed in its original left/right column instead (so the Ace “replaces” that card’s place).

If the middle cell for that row is already occupied by an Ace, then place that Ace in its original spot as normal.

After filling 5 rows, the dealing continues:

Start placing cards on top of existing cards in the left and right columns.

When stacking, cards on the left column are shifted left by 1/3 of the card width per stack level.

Cards in the right column are shifted right by 1/3 of the card width per stack level.

Aces still try to go to the middle cell for that row if it's free; if not, go to the normal left/right stack position.

Only the top card on each stack can be moved.

The middle column only holds Aces stacked vertically with no horizontal shift.

