# Battleship

> TCA Code Level 1 Semester 2 project

## Getting started

Open up Terminal or Command Prompt.

```
git clone https://github.com/tca-code/battleship

cd battleship
```

## Product Roadmap

- [ ] I can view a 10x10 grid for myself and my enemy
- [ ] I can place my ships on the board
  - **Ships**:
    1. Carrier (5 spaces)
    2. Battleship (4 spaces)
    3. Cruiser (3 spaces)
    4. Submarine (3 spaces)
    5. Destroyer (2 spaces)
  - **Rules**:
    1. Ships can be placed veritcally or horizontally
    2. Ships cannot be placed diagonally
    3. No part of a ship may hang over the edge of the board
    4. No ships may be placed on top of another ship
- [ ] I can guess an enemy ship location
  - **Rules**:
    1. On a 10x10 grid, submit the coordinates of an enemy ship (e.g. A1)
    2. If the coordinate contains any part of a ship, the enemy responds with "HIT"
    3. If the coordinate does not contain any part of a ship, the enemy responds with "MISS"
    4. The HIT OR MISS is recorded with an `X` on the enemy board (which is otherwise empty)
    5. If the attack was a HIT the background of the square is shaded to indicate a ship part
- [ ] An enemy can guess my ship location
  - **Rules**:
    1. On a 10x10 grid, the enemy submits the coordinates of its guess
    2. If the coordinate contains any part of a ship, you respond with "HIT"
    3. If the coordinate does not contain any part of your ship, you respond with "MISS"
    4. The HIT OR MISS is recorded with an `X` on your board
- [ ] Ships sink when all of their parts have been hit
- [ ] Game ends when all ships of a player have been sunk