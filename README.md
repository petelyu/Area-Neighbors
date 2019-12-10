# Area-Neighbors

These files list, in both long and wide formats, areas (e.g. Hospital Referral Regions) and their adjacent/neighboring areas.

General approach:
  1. Import shapefile into QGIS
  2. Convert area IDs into strings (if not already in string format)
  3. Execute Python script adapted from https://www.qgistutorials.com/en/docs/find_neighbor_polygons.html
      * Note: This creates a new attribute with comma-separated list of neighboring areas
  4. Export to CSV
  5. Execute R script to clean exported CSV into long- and wide-form data sets.
  
