# Description provenance

Provenance of the schema descriptions in `ogcapi-environmental-data-retrieval-1-oas31.bundled.json`: every description was authored from the standard's own requirements classes and prose — none imported.

| Schema | Source | Description (first sentence) |
|---|---|---|
| `DataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Property to contain any extra metadata information that is specific to an individual data query. |
| `anyAxis` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Validates any axis. |
| `areaDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR area query: the data of a collection within a user-defined polygon area. |
| `areaLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the results of an EDR area query. |
| `collection` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A collection available through this EDR API, with its parameter names, extents and data queries. |
| `collections` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A list of the collections available on this API, with their titles, descriptions and links. |
| `confClasses` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The conformance classes the deployment implements, per the OGC API conformance declaration. |
| `corridorDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR corridor query: the data along a user-defined path within a corridor width. |
| `corridorLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the results of an EDR corridor query. |
| `coverage` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A coverage: the data of a collection over its domain, per the OGC CIS model. |
| `coverageBase` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A Coverage, representing a mapping from a domain to sets of data values described by parameters. |
| `coverageCollection` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A collection of coverage objects. |
| `coveragejson` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A CoverageJSON object. |
| `crsObject` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A coordinate reference system object: either a well-known CRS identifier or a full WKT2 definition. |
| `cubeDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR cube query: the data of a collection within a user-defined 3-dimensional bounding box. |
| `cubeLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the results of an EDR cube query. |
| `domain` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The domain of a collection: the spatio-temporal axes over which its parameter values are defined. |
| `domainBase` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A Domain, which defines a set of positions and their extent in one or more referencing systems. |
| `edrFeatureCollectionGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A collection of EDR features serialized as GeoJSON, with locations and parameter values. |
| `edrProperties` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Properties to describe existing EDR features -- may be real-world or virtual sampling features. |
| `exception` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An exception report describing why a request failed, per the OGC API exception convention. |
| `extent` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The extent of the information in the collection. |
| `featureGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR feature serialized as GeoJSON. |
| `geometrycollectionGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A geometry collection serialized as GeoJSON. |
| `i18n` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Object representing an internationalised string where keys are BCP 47 language tags. |
| `i18n-2` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Object representing an internationalised string. |
| `instances` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The instances of a collection: distinct realizations of the data, such as model run dates. |
| `instancesDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Property to contain any extra metadata information that is specific to an individual data queries. |
| `instancesLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the instances of a collection. |
| `itemsDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Property to contain any extra metadata information that is specific to an individual data queries. |
| `itemsLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the items of a collection. |
| `landingPage` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The landing page of the API: links to the conformance declaration, collections and other resources. |
| `linestringGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A LineString geometry serialized as GeoJSON. |
| `link` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A hyperlink with its relation type, per the OGC API link conventions. |
| `locationsDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR locations query: the data at predefined locations of the collection. |
| `locationsLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the predefined locations of a collection. |
| `multilinestringGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A MultiLineString geometry serialized as GeoJSON. |
| `multipointGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A MultiPoint geometry serialized as GeoJSON. |
| `multipolygonGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A MultiPolygon geometry serialized as GeoJSON. |
| `ndArray` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Object representing a multidimensional (>= 0D) array with named axes, encoded as a flat one-dimensional array in row-major order. |
| `numberMatched` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The number of features of the feature type that match the selection
parameters like `bbox`. |
| `numberReturned` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The number of features in the feature collection. |
| `numericRegularlySpacedAxis` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A regularly-spaced numeric axis. |
| `numericValuesAxis` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Axis defined by list of numeric axis values and optional bounds. |
| `observedProperty` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A definition of the quantity being measured. |
| `observedProperty-2` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A definition of the quantity being measured. |
| `observedPropertyCollection` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Description of the property. |
| `parameter` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Represents metadata about the values of the coverage. |
| `parameter-2` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Represents metadata about the values of the coverage. |
| `parameterGroup` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Represents logical groups of parameters. |
| `parameterNames` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Definition of data parameter. |
| `pointGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A Point geometry serialized as GeoJSON. |
| `polygonGeoJSON` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A Polygon geometry serialized as GeoJSON. |
| `positionDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR position query: the data of a collection at a single coordinate. |
| `positionLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the results of an EDR position query. |
| `primitiveValuesAxis` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Validates any axis with primitive values. |
| `radiusDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR radius query: the data within a radius around a coordinate. |
| `radiusLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the results of an EDR radius query. |
| `referenceSystem` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A coordinate reference system for the spatial or temporal axes, per the OGC Topic 2 model. |
| `referenceSystemConnection` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Reference System Connection object: connects coordinates to reference systems. |
| `stringValuesAxis` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Simple axis with string values (e. |
| `targetConcept` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The concept or property an EDR query targets, identified by URI. |
| `tiledNdArray` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Object representing a multidimensional (>= 1D) array with named axes split up into sets of linked NdArray documents. |
| `trajectoryDataQuery` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | An EDR trajectory query: the data along a user-defined trajectory. |
| `trajectoryLink` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | A link to the results of an EDR trajectory query. |
| `unit` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The units of measure. |
| `unit-2` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The units of measure. |
| `units` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | definition of data units. |
| `valuesAxis` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | Validates any values-based axis. |
| `valuesAxisBase` | OGC 21-090 (Environmental Data Retrieval) requirements classes: the query family and the GeoJSON geometry family | The base definition of a values axis of a collection domain. |

These descriptions are offered upstream as part of the model-based publication program (metanorma-ogc#153); corrections by the editors are welcome and will be tracked here.
