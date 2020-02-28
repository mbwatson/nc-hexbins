# NC Map with D3-Hexbin

This is a data visualization proof-of-concept using [d3](https://d3js.org/) and [d3-hexbin](https://github.com/d3/d3-hexbin) over a geographical map.

Here, we have a state map of North Carolina (GeoJson extracted from [here](https://team.carto.com/u/piensaenpixel/tables/us_states_geojson/public)) on which 2000 points (longitude/latitude locations) are randomly generated and grouped into hexagonal bins.

View this demo [here](https://mbwatson.github.io/nc-hexbins/).

Buttons have been added to toggle visibibility of the points, the hexagonal mesh, and the bins. Additionally, users can export and download the current state of the image to a PNG file.
