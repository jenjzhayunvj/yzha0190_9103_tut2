# yzha0190_9103_tut2

## PART1:
The Packed Pavilion, shown at a paper-art exhibition in Shanghai at the close of World Expo 2010, which authors wrote a computer program that allowed the cones to combine with each other through a 3D circle packing process.
The main water sports venues for the 2008 Beijing Olympics, the Water Cube’s shell adopts the Weaire–Phelan foam, yielding irregular polygons (triangles, quadrilaterals, heptagons). 
Building on these precedents, I want to re-express “Wheels of Fortune” in 3D, based on circle packing. Adding shallow 3D forms heightens light–shadow contrast and rhythmic density, improving readability and immersion.


![An image of PP](readmeImages/PackedPavilion.png)
![An image of BJNA](readmeImages/TheBeijingNationalAquaticsCenter.jpg)


## PART2:

I’ll use a simple circle-packing routine in p5.js: seed circles, grow them each frame, and stop growth when an overlap is detected. This yields a non-overlapping, organic layout I can map to 3D by extruding each circle as a shallow cylinder (WEBGL). Radius-to-height/brightness and a slow rotation reinforce the “wheel” rhythm. Orbit control plus basic Lambert/emissive materials add clear light–shadow. The algorithm is short and parameter-driven (min gap, max radius), so I can tune density and structure to match my painting while staying within course scope.


![An image of Joe](readmeImages/Interwind.png)
[Link Text](https://openprocessing.org/sketch/2187000)


[Link Text](https://thecodingtrain.com/challenges/50-animated-circle-packing)
[Link Text](https://thecodingtrain.com/tracks/webgl/webgl/2-3d-geometries)
