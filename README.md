# Remote sensing, GO-BGC Data Workshop 2026

This tutorial shows people how to use [earthaccess](https://earthaccess.readthedocs.io/en/stable/) to download NASA Ocean Color Data. For run this tutorial, a [Nasa EarthData Login](https://urs.earthdata.nasa.gov/) is needed. Users additionally will need to create a [.netrc](https://nsidc.org/data/user-resources/help-center/creating-netrc-file-earthdata-login) file in their JupyterHub (or on their local machine).


## Access

To download the tutorial, navigate to the folder you want to download the repository into, then run: 

```
git clone https://github.com/go-bgc/tutorial-remote-sensing-2026.git
cd tutorial-remote-sensing-2026
ls # view the files
```

The file you'll need to open is:
1. `tutorial-remote-sensing.ipynb`: main Jupyter notebook that goes through an ML workflow

The other files in this repo are:
1. `setup.py`: contains path to BGC-Argo CrocoLake dataset (path set for JupyterHub, but will need to update if running locally)
2. `pace_matchup_fxns.py`: has functions for execute 5x5 matchups
