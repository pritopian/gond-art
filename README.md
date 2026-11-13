# Gond Scene

A hand-painted, Gond-inspired animated scene drawn entirely with the Canvas 2D API in one HTML file. No libraries, images or external assets.

Two deer drink at a grass bank beneath a tree full of fern fronds and birds; fish and a tortoise swim through patterned water. The piece loops every 24 seconds: the deer lower and lift their heads, a gust sways the tree, the birds wheel around it and leaves fall and turn colour.

Open `index.html` in a browser. Controls: Pause, Still (freezes motion), Sound (synthesized water, wind and birdsong) and a colour-theme picker (Earth, Monsoon, Dusk).

## p5.brush variant

`p5/index.html` is the same scene repainted with [p5.brush](https://github.com/acamposuribe/p5.brush) on p5.js 2 (loaded from jsDelivr, so it needs a network connection): watercolour fills with bleed and paper texture, pencil and pen strokes for contours and infill. Every static surface is brushed once into buffers at load, which takes 30–60 seconds; the animation runs on top.
