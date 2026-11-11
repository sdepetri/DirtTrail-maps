# DirtTrail maps

Public offline-map distribution for the DirtTrail Android app. Large PMTiles archives are
published as GitHub Release assets; `catalog.json` is the machine-readable catalog consumed by
the app.

## Current regions

| Region | Format | Zoom | Approx. size |
|---|---|---:|---:|
| San Luis, Argentina | PMTiles v3 / MVT | 0–15 | 44 MB |
| Mendoza, Argentina | PMTiles v3 / MVT | 0–15 | 80 MB |
| Córdoba, Argentina | PMTiles v3 / MVT | 0–15 | 125 MB |
| San Juan, Argentina | PMTiles v3 / MVT | 0–15 | 48 MB |
| La Rioja, Argentina | PMTiles v3 / MVT | 0–15 | 53 MB |

## Data and attribution

The current basemap archives are extracts of the Protomaps daily basemap, derived from
OpenStreetMap and Natural Earth. The tiles are Produced Works under the Open Database License
(ODbL). Applications displaying them must visibly show:

`© OpenStreetMap contributors`

- OpenStreetMap copyright: https://www.openstreetmap.org/copyright
- Protomaps basemap licensing: https://github.com/protomaps/basemaps#licensing-and-attribution-guidelines

The PMTiles specification is CC0 and its reference tools are BSD-3-Clause. Do not commit map
archives into Git history; attach them to releases instead.
