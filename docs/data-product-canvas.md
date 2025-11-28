
# Data Product Canvas - Berlin LOR Population

## Metadata

* owner: Open Lifeworlds
* description: Data product providing Berlin population data on different LOR hierarchy levels
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population
* license: CC-BY 4.0
* updated: 2025-11-06

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-lor-population

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-population-source-aligned/refs/heads/main/data-product-manifest.yml

## Transformation Steps

* [Data extractor](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/extract/data_extractor.py) extracts data from inout ports
* [Data blender](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/transform/data_blender.py) blends csv data into geojson files

## Output Ports

### berlin-lor-population-geojson
name: Berlin Lor Population Geojson
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/tree/main/data/03-gold/berlin-lor-population-geojson
* license: CC-BY 4.0
* updated: 2025-11-06

**Files**

* [berlin-lor-population-2015-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-01-city.geojson)
* [berlin-lor-population-2015-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-01-district-regions.geojson)
* [berlin-lor-population-2015-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-01-districts.geojson)
* [berlin-lor-population-2015-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-01-forecast-areas.geojson)
* [berlin-lor-population-2015-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-01-planning-areas.geojson)
* [berlin-lor-population-2015-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-02-city.geojson)
* [berlin-lor-population-2015-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-02-district-regions.geojson)
* [berlin-lor-population-2015-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-02-districts.geojson)
* [berlin-lor-population-2015-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-02-forecast-areas.geojson)
* [berlin-lor-population-2015-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2015-02-planning-areas.geojson)
* [berlin-lor-population-2016-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-01-city.geojson)
* [berlin-lor-population-2016-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-01-district-regions.geojson)
* [berlin-lor-population-2016-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-01-districts.geojson)
* [berlin-lor-population-2016-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-01-forecast-areas.geojson)
* [berlin-lor-population-2016-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-01-planning-areas.geojson)
* [berlin-lor-population-2016-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-02-city.geojson)
* [berlin-lor-population-2016-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-02-district-regions.geojson)
* [berlin-lor-population-2016-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-02-districts.geojson)
* [berlin-lor-population-2016-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-02-forecast-areas.geojson)
* [berlin-lor-population-2016-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2016-02-planning-areas.geojson)
* [berlin-lor-population-2017-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-01-city.geojson)
* [berlin-lor-population-2017-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-01-district-regions.geojson)
* [berlin-lor-population-2017-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-01-districts.geojson)
* [berlin-lor-population-2017-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-01-forecast-areas.geojson)
* [berlin-lor-population-2017-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-01-planning-areas.geojson)
* [berlin-lor-population-2017-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-02-city.geojson)
* [berlin-lor-population-2017-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-02-district-regions.geojson)
* [berlin-lor-population-2017-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-02-districts.geojson)
* [berlin-lor-population-2017-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-02-forecast-areas.geojson)
* [berlin-lor-population-2017-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2017-02-planning-areas.geojson)
* [berlin-lor-population-2018-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-01-city.geojson)
* [berlin-lor-population-2018-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-01-district-regions.geojson)
* [berlin-lor-population-2018-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-01-districts.geojson)
* [berlin-lor-population-2018-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-01-forecast-areas.geojson)
* [berlin-lor-population-2018-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-01-planning-areas.geojson)
* [berlin-lor-population-2018-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-02-city.geojson)
* [berlin-lor-population-2018-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-02-district-regions.geojson)
* [berlin-lor-population-2018-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-02-districts.geojson)
* [berlin-lor-population-2018-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-02-forecast-areas.geojson)
* [berlin-lor-population-2018-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2018-02-planning-areas.geojson)
* [berlin-lor-population-2019-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-01-city.geojson)
* [berlin-lor-population-2019-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-01-district-regions.geojson)
* [berlin-lor-population-2019-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-01-districts.geojson)
* [berlin-lor-population-2019-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-01-forecast-areas.geojson)
* [berlin-lor-population-2019-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-01-planning-areas.geojson)
* [berlin-lor-population-2019-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-02-city.geojson)
* [berlin-lor-population-2019-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-02-district-regions.geojson)
* [berlin-lor-population-2019-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-02-districts.geojson)
* [berlin-lor-population-2019-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-02-forecast-areas.geojson)
* [berlin-lor-population-2019-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2019-02-planning-areas.geojson)
* [berlin-lor-population-2020-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-01-city.geojson)
* [berlin-lor-population-2020-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-01-district-regions.geojson)
* [berlin-lor-population-2020-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-01-districts.geojson)
* [berlin-lor-population-2020-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-01-forecast-areas.geojson)
* [berlin-lor-population-2020-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-01-planning-areas.geojson)
* [berlin-lor-population-2020-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-02-city.geojson)
* [berlin-lor-population-2020-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-02-district-regions.geojson)
* [berlin-lor-population-2020-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-02-districts.geojson)
* [berlin-lor-population-2020-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-02-forecast-areas.geojson)
* [berlin-lor-population-2020-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2020-02-planning-areas.geojson)
* [berlin-lor-population-2021-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-01-city.geojson)
* [berlin-lor-population-2021-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-01-district-regions.geojson)
* [berlin-lor-population-2021-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-01-districts.geojson)
* [berlin-lor-population-2021-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-01-forecast-areas.geojson)
* [berlin-lor-population-2021-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-01-planning-areas.geojson)
* [berlin-lor-population-2021-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-02-city.geojson)
* [berlin-lor-population-2021-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-02-district-regions.geojson)
* [berlin-lor-population-2021-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-02-districts.geojson)
* [berlin-lor-population-2021-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-02-forecast-areas.geojson)
* [berlin-lor-population-2021-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2021-02-planning-areas.geojson)
* [berlin-lor-population-2022-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-01-city.geojson)
* [berlin-lor-population-2022-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-01-district-regions.geojson)
* [berlin-lor-population-2022-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-01-districts.geojson)
* [berlin-lor-population-2022-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-01-forecast-areas.geojson)
* [berlin-lor-population-2022-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-01-planning-areas.geojson)
* [berlin-lor-population-2022-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-02-city.geojson)
* [berlin-lor-population-2022-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-02-district-regions.geojson)
* [berlin-lor-population-2022-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-02-districts.geojson)
* [berlin-lor-population-2022-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-02-forecast-areas.geojson)
* [berlin-lor-population-2022-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2022-02-planning-areas.geojson)
* [berlin-lor-population-2023-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-01-city.geojson)
* [berlin-lor-population-2023-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-01-district-regions.geojson)
* [berlin-lor-population-2023-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-01-districts.geojson)
* [berlin-lor-population-2023-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-01-forecast-areas.geojson)
* [berlin-lor-population-2023-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-01-planning-areas.geojson)
* [berlin-lor-population-2023-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-02-city.geojson)
* [berlin-lor-population-2023-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-02-district-regions.geojson)
* [berlin-lor-population-2023-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-02-districts.geojson)
* [berlin-lor-population-2023-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-02-forecast-areas.geojson)
* [berlin-lor-population-2023-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2023-02-planning-areas.geojson)
* [berlin-lor-population-2024-01-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-01-city.geojson)
* [berlin-lor-population-2024-01-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-01-district-regions.geojson)
* [berlin-lor-population-2024-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-01-districts.geojson)
* [berlin-lor-population-2024-01-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-01-forecast-areas.geojson)
* [berlin-lor-population-2024-01-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-01-planning-areas.geojson)
* [berlin-lor-population-2024-02-city.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-02-city.geojson)
* [berlin-lor-population-2024-02-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-02-district-regions.geojson)
* [berlin-lor-population-2024-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-02-districts.geojson)
* [berlin-lor-population-2024-02-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-02-forecast-areas.geojson)
* [berlin-lor-population-2024-02-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-geojson/berlin-lor-population-2024-02-planning-areas.geojson)


### berlin-lor-population-statistics
name: Berlin Lor Population Statistics
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/tree/main/data/03-gold/berlin-lor-population-statistics
* license: CC-BY 4.0
* updated: 2025-11-06

**Files**

* [berlin-lor-population-statistics.json](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/03-gold/berlin-lor-population-statistics/berlin-lor-population-statistics.json)


## Observability

### Quality metrics

 * name: geojson_property_completeness
 * description: The percentage of geojson features that have all necessary properties

| Name | Value |
| --- | --- |
| berlin-lor-population-2015-01-city.geojson | 100 |
| berlin-lor-population-2015-01-districts.geojson | 100 |
| berlin-lor-population-2015-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2015-01-district-regions.geojson | 100 |
| berlin-lor-population-2015-01-planning-areas.geojson | 100 |
| berlin-lor-population-2015-02-city.geojson | 100 |
| berlin-lor-population-2015-02-districts.geojson | 100 |
| berlin-lor-population-2015-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2015-02-district-regions.geojson | 100 |
| berlin-lor-population-2015-02-planning-areas.geojson | 100 |
| berlin-lor-population-2016-01-city.geojson | 100 |
| berlin-lor-population-2016-01-districts.geojson | 100 |
| berlin-lor-population-2016-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2016-01-district-regions.geojson | 100 |
| berlin-lor-population-2016-01-planning-areas.geojson | 100 |
| berlin-lor-population-2016-02-city.geojson | 100 |
| berlin-lor-population-2016-02-districts.geojson | 100 |
| berlin-lor-population-2016-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2016-02-district-regions.geojson | 100 |
| berlin-lor-population-2016-02-planning-areas.geojson | 100 |
| berlin-lor-population-2017-01-city.geojson | 100 |
| berlin-lor-population-2017-01-districts.geojson | 100 |
| berlin-lor-population-2017-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2017-01-district-regions.geojson | 100 |
| berlin-lor-population-2017-01-planning-areas.geojson | 100 |
| berlin-lor-population-2017-02-city.geojson | 100 |
| berlin-lor-population-2017-02-districts.geojson | 100 |
| berlin-lor-population-2017-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2017-02-district-regions.geojson | 100 |
| berlin-lor-population-2017-02-planning-areas.geojson | 100 |
| berlin-lor-population-2018-01-city.geojson | 100 |
| berlin-lor-population-2018-01-districts.geojson | 100 |
| berlin-lor-population-2018-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2018-01-district-regions.geojson | 100 |
| berlin-lor-population-2018-01-planning-areas.geojson | 100 |
| berlin-lor-population-2018-02-city.geojson | 100 |
| berlin-lor-population-2018-02-districts.geojson | 100 |
| berlin-lor-population-2018-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2018-02-district-regions.geojson | 100 |
| berlin-lor-population-2018-02-planning-areas.geojson | 100 |
| berlin-lor-population-2019-01-city.geojson | 100 |
| berlin-lor-population-2019-01-districts.geojson | 100 |
| berlin-lor-population-2019-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2019-01-district-regions.geojson | 100 |
| berlin-lor-population-2019-01-planning-areas.geojson | 100 |
| berlin-lor-population-2019-02-city.geojson | 100 |
| berlin-lor-population-2019-02-districts.geojson | 100 |
| berlin-lor-population-2019-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2019-02-district-regions.geojson | 100 |
| berlin-lor-population-2019-02-planning-areas.geojson | 100 |
| berlin-lor-population-2020-01-city.geojson | 100 |
| berlin-lor-population-2020-01-districts.geojson | 100 |
| berlin-lor-population-2020-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2020-01-district-regions.geojson | 100 |
| berlin-lor-population-2020-01-planning-areas.geojson | 100 |
| berlin-lor-population-2020-02-city.geojson | 100 |
| berlin-lor-population-2020-02-districts.geojson | 100 |
| berlin-lor-population-2020-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2020-02-district-regions.geojson | 100 |
| berlin-lor-population-2020-02-planning-areas.geojson | 100 |
| berlin-lor-population-2021-01-city.geojson | 100 |
| berlin-lor-population-2021-01-districts.geojson | 100 |
| berlin-lor-population-2021-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2021-01-district-regions.geojson | 100 |
| berlin-lor-population-2021-01-planning-areas.geojson | 100 |
| berlin-lor-population-2021-02-city.geojson | 100 |
| berlin-lor-population-2021-02-districts.geojson | 100 |
| berlin-lor-population-2021-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2021-02-district-regions.geojson | 100 |
| berlin-lor-population-2021-02-planning-areas.geojson | 100 |
| berlin-lor-population-2022-01-city.geojson | 100 |
| berlin-lor-population-2022-01-districts.geojson | 100 |
| berlin-lor-population-2022-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2022-01-district-regions.geojson | 100 |
| berlin-lor-population-2022-01-planning-areas.geojson | 100 |
| berlin-lor-population-2022-02-city.geojson | 100 |
| berlin-lor-population-2022-02-districts.geojson | 100 |
| berlin-lor-population-2022-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2022-02-district-regions.geojson | 100 |
| berlin-lor-population-2022-02-planning-areas.geojson | 100 |
| berlin-lor-population-2023-01-city.geojson | 100 |
| berlin-lor-population-2023-01-districts.geojson | 100 |
| berlin-lor-population-2023-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2023-01-district-regions.geojson | 100 |
| berlin-lor-population-2023-01-planning-areas.geojson | 100 |
| berlin-lor-population-2023-02-city.geojson | 100 |
| berlin-lor-population-2023-02-districts.geojson | 100 |
| berlin-lor-population-2023-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2023-02-district-regions.geojson | 100 |
| berlin-lor-population-2023-02-planning-areas.geojson | 100 |
| berlin-lor-population-2024-01-city.geojson | 100 |
| berlin-lor-population-2024-01-districts.geojson | 100 |
| berlin-lor-population-2024-01-forecast-areas.geojson | 100 |
| berlin-lor-population-2024-01-district-regions.geojson | 100 |
| berlin-lor-population-2024-01-planning-areas.geojson | 100 |
| berlin-lor-population-2024-02-city.geojson | 100 |
| berlin-lor-population-2024-02-districts.geojson | 100 |
| berlin-lor-population-2024-02-forecast-areas.geojson | 100 |
| berlin-lor-population-2024-02-district-regions.geojson | 100 |
| berlin-lor-population-2024-02-planning-areas.geojson | 100 |


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

consumer-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).