### :balloon: Creating balloon animations for CesiumJS

Purpose: make it easy to replace the ballon animation in
https://cesiumjs.org/Cesium/Build/Apps/Sandcastle/?src=Cardboard.html
with a custom designed hull.

See also:  https://blog.mah.priv.at

### :rocket: Get Started ###

Prerequsites:
- [Inkscape](https://inkscape.org/en/release/inkscape-0.92.4/) to
  generate a texture
- [install the Kubicek fabric color palette into Inkscape]()
- [Blender 2.80](https://www.blender.org/download/) to project the texture
  onto the [balloon model from CesiumJS](https://github.com/AnalyticalGraphicsInc/cesium/tree/master/Apps/SampleData/models/CesiumBalloon)
- [Cesium Blender plugin](https://www.cesium.com/docs/tutorials/integrating-with-blender/)
to upload the result and host a reusable animations

Steps:
- clone this repo
- edit OE-SOE.svg as needed
- export as a PNG file, size 1024x1024
- open OE-SOE.blend in Blender
- in the Shading view, replace the file OE-SOE-graphic.png in the center node with your png
- adjust the Mapping X and Y Scale values until the projection looks ok
- export as .glb file (directly usable in a Cesium animation)
- and/or upload to Cesium.com with the Cesium Ion plugin

### :green_book: License ###

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). All custom files here, and files included from https://github.com/AnalyticalGraphicsInc/cesium .
