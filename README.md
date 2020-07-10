# Copernicus Global Land Service Resampling Tool Using R

This notebook shows how to resample Copernicus Global Land Service ([CGLS](https://land.copernicus.eu/global/)) vegetation-related products (i.e. NDVI, FAPAR...) from 333m resolution to 1km using R-based packages and functions.

It is intended for users who would like to continue temporarily their 1km time series, in near real time, before switching to the new 333m baseline resolution.

The user can apply the resample method shown here on older (non-near real time) 333m products and correlate the results with the 1km product of the same period. [This](https://github.com/xavi-rp/ResampleTool_notebook/blob/master/Resample_Report_v2.5.pdf) document provides the results of such comparisons between 1km-resampled and 1km-produced data layers.



