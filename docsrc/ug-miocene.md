---
title: Miocene
---

## Atmosphere
- [`atm-bc-topo.ipynb`](Miocene/MioMIP2/notebooks/atm-bc-topo.ipynb): converting the MioMIP2 Phase 2 CORE paleogeography into CAM-compatible `bnd_topo` boundary-condition files (`PHIS`, `LANDFRAC`, `LANDM_COSLAT`, `SGH`, `SGH30`) at **fv19**, **ne30**, and **ne120**, with two `SGH`/`SGH30` variants: regression on `PHIS`, and rotation-interpolation from the present-day reference topography.


## Ocean
- [`ocn-bc-kmt.ipynb`](Miocene/MioMIP2/notebooks/ocn-bc-kmt.ipynb): converting the MioMIP2 Phase 2 CORE paleogeography into the POP bathymetry (`KMT`), region mask, and SCRIP grid files on the standard **gx1v6** grid, with clean-up of the coastline, disconnected basins, islands, and the key ocean gateways.
