# Block Breaker
WebGL build of Block Breaker game.

[Play the game!](https://ryverine.github.io/BlockBreaker)

This game was created in Unity as part of the [Complete C# Unity Game Developer 2D](https://www.udemy.com/course/unitycourse/) course.

## How to Play

This is a [Breakout](https://en.wikipedia.org/wiki/Breakout_(video_game)) style game There are three main components of the game: the `Paddle`, the `Ball`, and the `Blocks`. Move the `Paddle` with the mouse. At the start of the game click the left mouse button to launch the `Ball` into the air. As the `Ball` will destroy `Blocks` that it hits. Your goal is clear the screen of all `Blocks` without letting the `Ball` fall past the `Paddle`.

## Special Blocks

The default `Block` will be destroyed after one hit of the `Ball`, but there are some `Blocks` with special behaviors.

### Unbreakable Blocks

Gray `Blocks` are unbreakable. They do not count toward your score and it is required to clear them in order to progress to the next level.

![Unbreakable Blocks](/Documentation/unbreakable_block.gif)

### Two-Hit Blocks

Orange `Blocks` will take two hits of the `Ball` to be destroyed.

![Two-Hit Blocks](/Documentation/two-hit_block.gif)

### Three-Hit Blocks

Red `Blocks` will take three hits of the `Ball` to be destroyed.

![Three-Hit Blocks](/Documentation/three-hit_block.gif)
