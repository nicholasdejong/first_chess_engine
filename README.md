# First Chess Engine (aka ChessLite)
I consider this to be my official first engine. Programmed in JavaScript, my intention was to fight it in the browser and debug it using the developer console, not to mention my proficiency in JavaScript at the time (now in favour of Rust). It has many problems and should not be considered a competitive chess engine, but it can still beat beginner players with ease.

## Problems
- The engine's legal move-generator is untested and might produce illegal moves in rare positions.
- The engine uses an inefficient board representation which has many performance repercussions.
- I was brand new to engine development and did not consider implementing the universal chess interface (UCI) for my engine, making the debugging and testing process a painful hassle.

This project is archived to prevent further changes. 
