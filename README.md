# Deep Species Distribution Models

A hands-on exercise in building deep learning Species Distribution Models (SDMs) with PyTorch, using Swiss biodiversity data from ***.

## Files

```
sdm_exercise.ipynb   # main notebook — start here
data/
  SWItrain_po.csv    # presence-only training records
  SWItrain_bg.csv    # background points
  SWItest_pa.csv     # presence-absence test labels
  SWItest_env.csv    # environmental covariates at test sites
  swi.gpkg           # Swiss border (GeoPackage)
  rasters/           # environmental raster layers (GeoTIFF)
```

## Requirements

```
torch
pandas
numpy
scikit-learn
matplotlib
rasterio
geopandas
```

Install with:

```bash
pip install torch pandas numpy scikit-learn matplotlib rasterio geopandas
```


