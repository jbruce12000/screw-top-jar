![screw top jar](https://raw.githubusercontent.com/jbruce12000/screw-top-jar/main/jar.png "screw top jar")

# Summary 

Easy customizer for making a screw top jar. 

# Features

- round or faceted [square, hexagon, octagonal etc]
- diameter of the jar depends on the thread you pick
- knurling for easier grip to open/close
- threaded height on both top and bottom are configurable
- unthreaded height on both top and bottom are configurable 


## Instructions

- Download openscad and open the scad file...
- or use the thingiverse customizer [here](https://www.thingiverse.com/)
- configure Overall details like thread and sides...
- configure sizes for top and bottom
- create an stl file 
- print

## Helpful Details

- the threaded height on the top should be a few mm greater than the bottom or there will be a gap between top and bottom
- the fewer sides you have, the larger the wall thickness must be
- see [threads](https://gist.github.com/jbruce12000/24565ca20c765bd26c7971655129ab01) to pick a jar size 
- the diameter of the inside of the jar will be int_diameter - (2 * wall thickness)
- the diameter of the outside of the jar will be ext_diameter + (2 * wall thickness) 
