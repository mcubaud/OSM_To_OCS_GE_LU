# OSM_To_OCS_GE_LU
Describe how to attribute to some OSM points and polygons a OCS GE Land Use class.

The file OSM_to_OCSGE.ods gives the mapping from OSM tags to OCSGE classes. First column gives a key that for all the values of the second column, if the conditions of the third column are met, is mapped to the LU class of the fourth column.
- *any* in the value columns means that the relationship between the key and the LU class is independant of the value for the key.
- *all others* means that the key is mapped to the LU class for any of the values that are not in other rows with this key.
