# nantlab-workshop-cc-visuals-impex-2023
## content
1. Basics
* coordinate system
* colors
* shapes
* variables
* if
* for
* functions (map, sin, millis, ...)
2. interaction
* mouse/keyboard: https://editor.p5js.org/thomasgeissl/sketches/ttHYj22Rw
* midi: https://editor.p5js.org/thomasgeissl/sketches/ivhb5YdKU
* mqtt (popeye): https://editor.p5js.org/thomasgeissl/sketches/hcx44o_10
* audio reactive: https://editor.p5js.org/thomasgeissl/sketches/krtVDP_9S


## snippets
### save snapshot
```
function keyReleased() {
  if (key === 's') {
    saveCanvas('myCanvas', 'png');
  }
}
```

## tools
* mqtt broker: https://github.com/thomasgeissl/ragazzi/releases/
* midi monitor: https://hexler.net/protokol#get
* virtual midi device on windows: https://www.tobias-erichsen.de/software/loopmidi.html

## further links
p5js collection: https://editor.p5js.org/thomasgeissl/collections/1aVAFOdmq
p5js documentation: https://p5js.org/reference/
p5js tutorials: daniel shiffman, coding train, the nature of code
* https://www.youtube.com/watch?v=70MQ-FugwbI
* https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw
