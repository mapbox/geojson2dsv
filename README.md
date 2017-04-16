[![Build Status](https://travis-ci.org/tmcw/geojson2dsv.svg)](https://travis-ci.org/tmcw/geojson2dsv)
[![Coverage Status](https://coveralls.io/repos/tmcw/geojson2dsv/badge.svg)](https://coveralls.io/r/tmcw/geojson2dsv)
[![Greenkeeper badge](https://badges.greenkeeper.io/tmcw/geojson2dsv.svg)](https://greenkeeper.io/)

# geojson2dsv

The reverse of [csv2geojson](https://github.com/mapbox/csv2geojson): shuttle [GeoJSON](http://geojson.org/) points into
CSV encoding.

Currently points only.

## api

### `csvString = geojson2dsv(geojsonObject)`

Given a valid GeoJSON object, return a CSV composed of all decodable points.

## see also

* [geojson2csv](https://github.com/morganherlocker/geojson2csv) also does this, but has file-assumptions and does dsv encoding in-house instead of farming it out to mbostock/dsv
