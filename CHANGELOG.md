# Changelog

## :package: [1.1.1](https://pypi.python.org/pypi/arcgis2geojson/1.1.1) - 2018-02-28

Bugfix: Require `six` in setup.py

## :package: [1.1.0](https://pypi.python.org/pypi/arcgis2geojson/1.1.0) - 2018-02-26

Improve compliance with RFC 7946:

* Wind outer rings counterclockwise and inner rings clockwise
* Prevent values other than string or number in id field
* Convert but log a warning if input SRID is not 4326

## :package: [1.0.4](https://pypi.python.org/pypi/arcgis2geojson/1.0.4) - 2017-12-29

Bugfix: Preserve Z-values if present in input geometry

## :package: [1.0.3](https://pypi.python.org/pypi/arcgis2geojson/1.0.3) - 2017-10-26

Bugfix: Fix install under python 2.7

## :package: [1.0.2](https://pypi.python.org/pypi/arcgis2geojson/1.0.2) - 2017-10-25

Distribute via PyPI

## :package: 1.0.1 - 2017-07-21

Bugfix: If geometry is empty or invalid, return None

## :package: 1.0.0 - 2017-01-10

First Release