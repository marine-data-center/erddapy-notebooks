# erddapy-notebooks
Repository for containing ERDDAPy usage examples. Points to the MDC's MarineFlux ERDDAP servers. 

## ERDDAPy_Anaylsis_ICOADS.ipynb
Ths Jupyter notebook demonstrates using erddapy to query the ICOADS flux dataset on the MarineFlux ERDDAP server, requesting a subset of data from different algorithms as a series of xarray Datasets, then plotting the variable data as a histogram. Made by Amanda Lovett.

## samos.ipynb
This Jupyter notebook demonstrates using erddapy to query the SAMOS fluxes dataset on the MarineFlux ERDDAP server, requesting a subset as various types of python objects (netCDF4-python object, pandas DataFrame, xarray Dataset), filtering out data not flagged as "good", and plotting the data on a map in a few different ways. Made by Marc Castells.

## histo.ipynb
This Jupyter notebook demonstrates using erddapy to query the SAMOS fluxes dataset on the MarineFlux ERDDAP server, requesting a subset as an xarray Dataset, filtering out data not flagged as "good", and plotting histograms of each of the variables. Made by Marc Castells.
