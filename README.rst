## Overview

This repo contains code I've used to explore Uber surge pricing in Manhattan on May 24-25, 2016, accompanying a post on my personal blog. 

Ping Uber API IPython Notebook: contains the code used to pull the surge pricing from the API. All you need is a API server token. See the [Uber Python API Repo](https://github.com/uber/rides-python-sdk) for documentation. The points I query for surge pricing are constructed from NYC OpenData [database](https://nycopendata.socrata.com/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/xx67-kt59) of Restaurant Inspections.

Pretty Plots: Extension of code found [here](http://sensitivecities.com/so-youd-like-to-make-a-map-using-python-EN.html#.V0y1JfkrLIU) to plot Manhattan in a clean and customizable manner. The plots use the Basemap python module. 