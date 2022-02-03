# OGC GeoSPARQL Extended Shapes

This repository conatains constraints that are not required for core GeoSPARQL use but are useful for particular scenario use.

## Background

The [OGC's GeoSPARQL standard](https://www.ogc.org/standards/geosparql) is [Semantic Web](https://www.w3.org/standards/semanticweb/) data model and defined set of functions that indicates how to represent and use spatial data in Semantic Web form.

The latest version of GeoSPARQL, [GeoSPARQL 1.1](https://opengeospatial.github.io/ogc-geosparql/geosparql11/spec.html), includes a nubmer of *shapes* or *shapes graph* which are [SHACL](https://www.w3.org/TR/shacl/) data objects that can be used to validate data claiming to conform to GeoSPARQL.

GeoSPARQL 1.1 contains a [SHACL graph for core requirements](https://github.com/opengeospatial/ogc-geosparql/blob/master/1.1/validator.ttl).

This repository contains additional GeoSPARQL constraints in SHACL graphs that are not required for core GeoSPARQL use but are useful for particular scenario use.

## Content

### Consistency

Shapes graphs in this repository are not guarenteed to be consistent and may be conflicting, i.e. it may be that for your data to pass on validator stored here, it will necissarily fail another! So use the shapes here either independently or after carfully selecting them: don't just use them all in one go.

### Community

These shapes graphs are managed here by the [OGC's GeoSemantics Domain Working Group](https://www.ogc.org/projects/groups/semantics) but contributed by the GeoSPARQL community, therefore they vary in style. Just be aware that there is not yet a hard methodology to harmonise them.

### Catalogue

The shapes in this repository are presented in RDF files in the Turtle format within folders listed below. Metadata about who created the files and what they are for is present in comments at the top of each file and in README files in folders.

## Shapes

## Contact

For all matters relating to this repository's content, please contact either the [Geosemantics DWG](https://www.ogc.org/projects/groups/semantics) or the individual authors of the shapes, given in metadata.
