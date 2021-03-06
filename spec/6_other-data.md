## 2.5. Other Data Tables 

Application-specific or vendor-specific data tables that do not conform to the table definitions or
other requirements for storing feature data, raster or tile data, or metadata as defined in other
sections of this document MAY be defined and used to store supplemental information in a GeoPackage
database. Such other data tables MAY be described by rows in the `gpkg_spatial_ref_sys`,
`gpkg_contents`, `gpkg_geometry_columns`, `gpkg_extensions`, `gpkg_data_columns`,
`gpkg_tile_matrix_metadata`, `gpkg_metadata` and `gpkg_metadata_reference` tables. GeoPackage
applications MAY ignore such descriptive rows and other data tables they do not recognize.
