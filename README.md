# Georeferencing of historical maps
## Overview
This project explores feature-based and coordinate-based georeferencing workflows in ArcGIS Pro.

The objective was to evaluate different transformation methods, assess positional accuracy, and identify common sources of georeferencing error when working with historical maps.

## Data
- Historical Map of Austria. Source: David Rumsey Map Collection, David Rumsey Map Center, Stanford University Libraries. "Karta öfver Österrike" (1821) (https://www.davidrumsey.com)
- USGS Jersey City Map. Source: USGS TopoView, Year: 1955, Projection: NAD 1927 (https://ngmdb.usgs.gov/topoview/)

## Methods
1. Feature-based georeferencing for the Austrian map:

- Historical map cropped and imported into ArcGIS Pro
- Ground control points collected from coastlines and major cities
- 1st-, 2nd- and 3rd-order polynomial transformations tested
- RMS errors evaluated
- Visual comparison with reference data performed
 -Coordinate-based georeferencing
  
2. Coordinate-based georeferencing for the USGS map:

- Coordinate ticks digitised from the map frame
- Coordinates entered in NAD 1927
- First-, second- and third-order transformations compared

## Results
1. Historical Austria Map
- The 2nd-order polynomial transformation produced the best balance between positional accuracy and visual map quality.
- The 3rd-order transformation achieved lower RMS values but introduced noticeable edge distortion.

2. USGS Jersey City Map
- Coordinate-based georeferencing produced substantially higher positional accuracy than feature-based georeferencing.

## Key Findings
- Lower RMS values do not automatically indicate a better georeferencing result.
- Visual inspection remains an important validation step.
- Coordinate-based georeferencing can provide substantially higher positional accuracy than feature-based approaches.
- Control point distribution strongly influences final accuracy.

## Tools
- ArcGIS Pro
- GIMP

## Skills Demonstrated
- Georeferencing
- Historical GIS
- Spatial accuracy assessment
- Transformation selection
- Control point evaluation
- Cartographic analysis
