# Mean Sea Surface, Gravity, and Bathymetry Prediction Workshop
## Objectives: The main objective of this workshop is to develop best practices for predicting bathymetry from a combination of sparse ship soundings and marine gravity from SWOT altimetry. A secondary objective is to develop best practices for constructing a mean sea surface (MSS) and other gravity products from SWOT.


## Prediction Competition: During the workshop we will have an informal competition using three data sets: SWOT gravity, SRTM soundings (training data), and unique GEBCO soundings (evaluation data). Participants can use any other data/information but will not have access to the unique GEBCO soundings which will be used for evaluation.

### We will use the global predicted bathymetry published by Harper et al., 2023 as a baseline. It uses a straightforward ML approach and the pre-SWOT gravity.  Here is a link to that paper.
https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023EA003199

### All the data and software needed to reproduce the results are at this Zenodo site referenced in the paper.
https://zenodo.org/records/8029925 

### If you would like to try this approach using the new SWOT gravity, the replacement files are at the following site.

https://topex.ucsd.edu/pub/global_grav_1min_SWOT/prediction_files/ 


### We started with the grav_on_topo_SWOT_01.img  gravity but that was updated with grav_on_topo_SWOT_02.img which has more data.  The gravity data are at the site 

https://topex.ucsd.edu/pub/global_grav_1min_SWOT/


### As discussed below, the rms evaluation will use unique GEBCO soundings not available in the SRTM ship data.  In addition we will use seamount summits depths published in this paper.

https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022EA002331 


### The summit depth file is here.

https://topex.ucsd.edu/pub/global_grav_1min_SWOT/prediction_files/summit.xyd 
