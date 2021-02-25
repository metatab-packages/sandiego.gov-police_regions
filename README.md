
# San Diego Police Regions and Demographics

This package links shapefiles for San Diego police beats to Census tracts and
merges in ACS estimates for population, by race, from the 2016 5 year ACS. When
a police beat boundry crosses a tract, the tract population is allocated to
beats by the proportion of the overlap by area. See the [Jupyter
notebook](https://nbviewer.jupyter.org/github/metatab-packages/sandiego.gov-police_regions/blob/master/notebooks/BeatPopulations.ipynb) that
performs the procedure for details.

For the race/ethicty statistics, Hispanic ('hisp') refers to Hispanics of any
race, while all other races refer to non-Hispanics of that race.
