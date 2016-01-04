# Functions for making thematic maps in R

This repository is based off of a research project about identifying high need areas in South Carolina. While the high need and South Carolina parts of this project may not particularly interest you, you may be interested in how I thematically mapped data not in ArcGIS, but in R.

This project relies on several R libraries, but especially the tmap and rgdal libraries.

While you may find it useful to look at my final maps, reports, and source data, the most useful part of this repository for you is probably my R functions. I have three functions that each serve a purpose:

The first one reads a shapefile into R, and joins it to a csv based on a geographic area unit (in my case it was ZCTAs in SC). The output provided data needed for the thematic mapping function.
The second function takes the output from the first, and thematically maps it.
The final function takes values from several different maps (created using the first two functions, just uses 4 iterations of the first 2), and creates a new map based on the results of those 4 iterations.

The other folders contain maps I created with these functions, my source data, other output, my research paper, etc. Feel free to use this to get ideas! But also, please do not use my work word for word. I say this because while this is one way to make maps in R, there are so many other ways to do it. My ways may not be the best ways, as I have a social science background and not a programmer background.

Thanks and I hope this helps! If you know wayas to improve my approach, please feel free to reach out.
-Rachel
