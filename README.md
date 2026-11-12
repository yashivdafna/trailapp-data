# TrailApp map data

Region files the TrailApp hiking app downloads once and uses offline. Each GitHub release holds one
region version: `region-israel.json` (file list with sizes, SHA-256 and data dates) and the files it lists.
The app reads the newest release: `releases/latest/download/region-israel.json`.

| File | What | Source and licence |
|---|---|---|
| `israel-basemap-*.pmtiles` | base map (roads, places, land use) | © OpenStreetMap contributors, ODbL 1.0; Protomaps basemap build |
| `israel-trails.pmtiles` | marked hiking trails | © OpenStreetMap contributors, ODbL 1.0 |
| `israel-outdoor.pmtiles` | springs, wells, viewpoints, caves, ruins, camps, shelters, firing zones, sand and rock | © OpenStreetMap contributors, ODbL 1.0 |
| `israel-terrain-glo30-q1.pmtiles` | terrain shading (heights rounded to 1 m) | Copernicus GLO-30 DEM: © DLR e.V. 2010-2014 and © Airbus Defence and Space GmbH 2014-2018, provided under COPERNICUS by the European Union and ESA |
| `israel-contours.pmtiles` | contour lines (10 m, every 50 m bold) | made from Copernicus GLO-30 DEM (same notice) |
| `E30_N25.rd5` ... `E35_N30.rd5` | routing data for BRouter | brouter.de segments4, © OpenStreetMap contributors, ODbL 1.0 |

The OpenStreetMap-based files are offered under the Open Database License 1.0
(https://opendatacommons.org/licenses/odbl/1-0/). Copernicus data: see the Copernicus DEM licence.
