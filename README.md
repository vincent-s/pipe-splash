# Pipe Splash

A browser puzzle game inspired by Pipe Dream. Water leaves the red valve after a countdown and creeps through the grid. Place pipe pieces from the queue to guide it into the green drain before it spills.

## Play

Open `index.html` in any modern browser. No build step or install is needed.

## Rules

- Click a tile to place the highlighted pipe from the queue.
- Click an empty pipe you already placed to swap it for the next piece (costs 25 points).
- The water must enter the drain through its open side.
- Every pipe the water fills scores 50. Cross pieces can be filled twice.
- Press **Open valve now** to skip the countdown, or **Speed up water** once it's flowing.
- Keyboard: arrow keys move the cursor, Enter or Space places a pipe.

## Difficulty

| Level  | Grid    | Obstacles | Countdown |
|--------|---------|-----------|-----------|
| Easy   | 7 × 7   | 0         | 25 s      |
| Medium | 9 × 9   | 4         | 20 s      |
| Hard   | 12 × 12 | 9         | 16 s      |

The water also moves faster on harder levels. Every board is checked to have at least one open route from the valve to the drain.
