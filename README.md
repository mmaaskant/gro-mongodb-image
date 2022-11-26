# Gro - MongoDB Image
> An extension of the MongoDB image, adding initial indexes.

These indexes contain the required fields for scraping, mapping and compiling data collected by Gro.

## Features

The initial indexes can be found in `/compose/init_db.js` and are added to the Image using MongoDB's
`docker-entrypoint-initdb.d` feature.

## Licensing

The code in this project is licensed under an GPL-3.0 license.