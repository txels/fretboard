# Fretboards on a browser

Instantiate a fretboard, and display some notes, scales, chord voicings, etc.

Examples:

```js
// Layout a specific scale
var fb = Fretboard();
fb.draw("a phrygian");

// Use alternative tunings
var fbDropD = Fretboard({tuning: Tunings.Drop_D});
fbDropD.draw("a phrygian");

// Place specific notes on specific strings, e.g. for chord voicings
var c7add9 = Fretboard({frets: 5});
c7add9.draw("5:c3 4:e3 3:bb3 2:d4 1:g4");
```
