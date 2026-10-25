# Minesweeper in Java

A desktop implementation of Minesweeper, with a grid-based game model, flagging, neighbouring-cell expansion and a graphical interface.

## Play

Open the project with **Java 17 or newer**, mark `res/` as the resource root and run the `Minesweeper` class. The image resources must be available on the runtime classpath.

- Left-click to reveal a cell.
- Right-click to place or remove a flag.
- Click an opened numbered cell to reveal its remaining neighbours when the adjacent flag count matches the number.

The board contains ten mines. Reveal every safe cell to win; revealing a mine ends the game.

## Code map

| Source | Responsibility |
| --- | --- |
| [Minesweeper.java](src/Minesweeper.java) | Desktop interface and input handling |
| [Game model](src/sweeper/) | Board state, mines, flags, coordinates and game transitions |
| [Resources](res/img/) | Cell and interface images |

Compiled artifacts are retained from the original coursework. The source is the preferred entry point for inspecting the implementation.
