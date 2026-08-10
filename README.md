# Sea Isle City Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Sea Isle City municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01411350, Sea Isle
- PETSS / NOAA station: 8535221
- NAVD88 thresholds: 3.35 ft minor, 4.35 ft moderate, 5.35 ft major
- MLLW thresholds: 5.7 ft minor, 6.7 ft moderate, 7.7 ft major
- MLLW = NAVD88 + 2.35 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Sea Isle City boundary at 5.8-foot adaptive resolution.
