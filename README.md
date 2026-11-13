# Topping Out

A crane game for ironworkers. You're in the seat of a tower crane. Stand the columns, hang the beams, and top out the building without banging up the iron.

## Play

Open `index.html` in any browser. It's one file with no build step and no dependencies.

To host it free, turn on GitHub Pages for this repo (Settings > Pages > Deploy from branch > main, root folder). The game will be live at `https://<your-username>.github.io/<repo-name>/`.

## Controls

| Action | Touch | Keyboard |
| --- | --- | --- |
| Trolley left and right | Drag anywhere | Left / Right or A / D |
| Cable down | Hold CABLE DOWN | Down or S |
| Cable up | Hold CABLE UP | Up or W |

Tap the cable buttons to creep. Hold them to run.

## How it works

- 14 pieces over 4 floors. Six two-story columns and eight beams. The last beam is the white one with the flag and the tree.
- The load swings on the line. Chase it with the trolley to catch the swing.
- Bring a piece in close and quiet and the connectors grab it and walk it home. Beams get a tag line.
- Land a piece at a run, hit a column, or miss the anchor bolts and it counts as a bang.
- Clean sets in a row stack a score multiplier. Finishing a level pays a bonus. Bangs cost points and reset the multiplier.
- Wind picks up every floor.
- Finish with a top 20 score and you post your initials to the high score board. Scores are saved in the browser on that device. There is no server, so every device has its own board.

## Files

- `index.html` is the whole game. Markup, styles and script are all in it.

Fonts load from Google Fonts. Everything else is drawn on a canvas and the sound is synthesized in the browser, so there are no image or audio assets.
