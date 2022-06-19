[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct-single.svg)](https://vshymanskyy.github.io/StandWithUkraine)

[![RussianWarship](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/RussianWarship.svg)](https://vshymanskyy.github.io/StandWithUkraine)

Source: 
[StandWithUkraine](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/AddBanner.md)

# python_gis
Collection of short geospatial scripts and more....

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Daily updated - Global CO<sub>2</sub> Trend
<img src=Climate/09_DailyGlobalCO2.jpg width="600">

## Daily updated - Vaccination share vs Covid-19 deaths/mln (EU-27) from 2021/09/01
<img src=COVID/01_Vax_vs_Deaths_Biv_Map.jpg width="600">

### [Python](https://github.com/ivandorte/python_gis/tree/main/Python)

* [Check if a series of points are inside a circle](https://github.com/ivandorte/python_gis/blob/main/Python/01_points_inside_circle_loop.ipynb)

### [Matplolib](https://github.com/ivandorte/python_gis/tree/main/Matplotlib)

* [Add a watermark to a figure](https://github.com/ivandorte/python_gis/blob/main/Matplotlib/01_watermark.ipynb)

### [Plotnine](https://github.com/ivandorte/python_gis/tree/main/Plotnine)

* [Small multiple maps](https://github.com/ivandorte/python_gis/blob/main/Plotnine/01_small_multiples.ipynb)

### [Numpy](https://github.com/ivandorte/python_gis/tree/main/Numpy)

* [Check if a series of points are inside a circle - Vectorized](https://github.com/ivandorte/python_gis/blob/main/Numpy/01_points_inside_circle_vect.ipynb)
* [Create a fishnet of rectangular cells](https://github.com/ivandorte/python_gis/blob/main/Numpy/02_fishnet.ipynb)

### [Numba](https://github.com/ivandorte/python_gis/tree/main/Numba)

* [Slope, Aspect, Hillshade](https://github.com/ivandorte/python_gis/blob/main/Numba/01_terrain_algs.ipynb)
* [Random walk 2D](https://github.com/ivandorte/python_gis/blob/main/Numba/02_random_walk.ipynb)
* [Smooth raster](https://github.com/ivandorte/python_gis/blob/main/Numba/03_smooth_raster.ipynb)

### [Mobility](https://github.com/ivandorte/python_gis/tree/main/Mobility)
* [TomTom Traffic index](https://github.com/ivandorte/python_gis/blob/main/Mobility/01_TomTom_traffic.ipynb)

### [Networks](https://github.com/ivandorte/python_gis/tree/main/Networks)

* [Basic network analysis - OSMnx](https://github.com/ivandorte/python_gis/blob/main/Networks/01_osmnx.ipynb)
* [Basic network analysis - python-igraph](https://github.com/ivandorte/python_gis/blob/main/Networks/02_igraph.ipynb)

### [LP](https://github.com/ivandorte/python_gis/tree/main/LP)

* [TSP](https://github.com/ivandorte/python_gis/blob/main/LP/01_tsp.ipynb)

### [Shapely](https://github.com/ivandorte/python_gis/tree/main/Shapely)

* [Basics geometric operations](https://github.com/ivandorte/python_gis/blob/main/Shapely/01_gis_basics_shapely.ipynb)
* [Nearest point on line/polygon](https://github.com/ivandorte/python_gis/blob/main/Shapely/02_nearest_point_on_line_polygon.ipynb)
* [Generate points along line](https://github.com/ivandorte/python_gis/blob/main/Shapely/03_points_along_line_shapely.ipynb)
* [Divide line in equal parts](https://github.com/ivandorte/python_gis/blob/main/Shapely/04_divide_line_in_equal_parts.ipynb)
* [Rtree spatial indexing](https://github.com/ivandorte/python_gis/blob/main/Shapely/05_rtree.ipynb)

### [GDAL](https://github.com/ivandorte/python_gis/tree/main/GDAL)

* [Basic DEM processing](https://github.com/ivandorte/python_gis/blob/main/GDAL/01_dem_processing.ipynb)
* [Smooth contours](https://github.com/ivandorte/python_gis/blob/main/GDAL/02_gen_contours.ipynb)

### [OSM](https://github.com/ivandorte/python_gis/tree/main/OSM)

* [Query Overpassturbo](https://github.com/ivandorte/python_gis/blob/main/OSM/01_overpassturbo.ipynb)

### [Scikit-image](https://github.com/ivandorte/python_gis/tree/main/Scikit-image)

* [Least cost path - WIP](https://github.com/ivandorte/python_gis/blob/main/Scikit-image/01_least_cost_path.ipynb)

### [Climate](https://github.com/ivandorte/python_gis/tree/main/Climate)

* [No-Atmosphere Climate Model](https://github.com/ivandorte/python_gis/blob/main/Climate/01_no_atmosphere_model.ipynb)
* [One-Layer Atmosphere Model](https://github.com/ivandorte/python_gis/blob/main/Climate/02_one_layer_atmosphere_model.ipynb)
* [One-Layer Atmosphere Model - CO2, H2O](https://github.com/ivandorte/python_gis/blob/main/Climate/03_one_layer_atmosphere_CO2_H2O_model.ipynb)
* [Zero dimensional EBM - Albedo](https://github.com/ivandorte/python_gis/blob/main/Climate/04_zero_dimensional_albedo_feedback_model.ipynb)
* [Radiative-Convective Model](https://github.com/ivandorte/python_gis/blob/main/Climate/05_radiative_convective_model.ipynb)
* [Shoebox Model](https://github.com/ivandorte/python_gis/blob/main/Climate/06_global_climate_shoebox_model.ipynb)
* [Energy Balance Climate Model](https://github.com/ivandorte/python_gis/blob/main/Climate/07_energy_balance_climate_model.ipynb)
* [Energy Balance Climate with Seasons](https://github.com/ivandorte/python_gis/blob/main/Climate/08_energy_balance_climate_seasons_model.ipynb)
* [Daily updated - Global CO2 Trend](https://github.com/ivandorte/python_gis/blob/main/Climate/09_global_trends_CO2.ipynb)

### [COVID](https://github.com/ivandorte/python_gis/tree/main/COVID)

* [Daily updated - Vaccinated vs Deaths Bivariate Map (EU-27)](https://github.com/ivandorte/python_gis/blob/main/COVID/01_Vax_vs_Deaths_Biv_Map.ipynb)
