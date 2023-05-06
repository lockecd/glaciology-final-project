# Incorporating Bed Topography into a Shallow-Ice Approximation Model

Caitlin Locke <br />
Glaciology Final Project <br />
Spring 2023 <br />

## 1) Final Project Information

## Background and Motivation

For our Shallow Ice Approximation model, we assumed a flat bed topography. In reality, ice sheets do not flow over a flat bed, but a varying bed topography. Beneath the Antarctic Ice Sheet, the bed topography is dynamic and geologically controlled.

## Scientific Question

How does the addition of bed topography effect our model results and ice sheet dynamics? In particular, how do different bed topography geometries effect ice sheet dynamics in different Antarctic drainage systems in Antarctica?

## Datasets

1. [Bedmap2 - Ice thickness and subglacial topographic model of Antarctica](https://www.bas.ac.uk/project/bedmap-2/)
1. [MEaSUREs BedMachine Antarctica, Version 3](https://nsidc.org/data/nsidc-0756/versions/3)
1. [MEaSUREs Antarctic Boundaries for IPY 2007-2009 from Satellite Radar, Version 2](https://nsidc.org/data/nsidc-0709/versions/2)

## Summary of Analysis

I will write a new spatially-varying bed function that allows the bed elevation to vary over distance, and I will incorporate bed topography data from BedMap2 and Bedmachine2 into my shallow-ice approximation model. To do this I will sample BedMap2 and BedMachine3 bed topography onto lines generated from two points picked using the interactive code from Jonny Kingslake's Glaciology Practical 5 in order to examine the model output over different bed topographies in Antarctica. Once these two steps are completed, I will overlay the Antarctic drainage systems from Zwally et al., 2012 on the Bedmap2 and BedMachine2 bed topography and run the model over multiple major drainage basins in order to examine the effect of different bed topography geometries on ice sheet dynamics in these regions. 


## References

1. Fretwell, P., Pritchard, H. D., Vaughan, D. G., Bamber, J. L., Barrand, N. E., Bell, R., Bianchi, C., Bingham, R. G., Blankenship, D. D., Casassa, G., Catania, G., Callens, D., Conway, H., Cook, A. J., Corr, H. F. J., Damaske, D., Damm, V., Ferraccioli, F., Forsberg, R., … Zirizzotti, A. (2013). Bedmap2: Improved ice bed, surface and thickness datasets for Antarctica. The Cryosphere, 7(1), 375–393. https://doi.org/10.5194/tc-7-375-2013
1. Morlighem, M. (2022). MEaSUREs BedMachine Antarctica, Version 3 [Data Set]. Boulder, Colorado USA. NASA National Snow and Ice Data Center Distributed Active Archive Center. https://doi.org/10.5067/FPSU0V1MWUB6. Date Accessed 05-05-2023.
1. Mouginot, J., B. Scheuchl, and E. Rignot. (2017). MEaSUREs Antarctic Boundaries for IPY 2007-2009 from Satellite Radar, Version 2 [Data Set]. Boulder, Colorado USA. NASA National Snow and Ice Data Center Distributed Active Archive Center. https://doi.org/10.5067/AXE4121732AD. Date Accessed 05-05-2023.
1. Zwally, H. Jay, Mario B. Giovinetto, Matthew A. Beckley, and Jack L. Saba, 2012, Antarctic and Greenland Drainage Systems, GSFC Cryospheric Sciences Laboratory, at http://icesat4.gsfc.nasa.gov/cryo_data/ant_grn_drainage_systems.php.
