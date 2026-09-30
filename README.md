# Outerview Crimes

Outerview  
A research lab building world models.

Outerview is a research lab focused on understanding the physical world at planetary scale.

We are building systems that can organize the world’s physical information and make it accessible and usable — transforming raw imagery, video, location, and spatial context into knowledge that people and machines can search, interpret, and act on.

Our belief is simple: the physical world should be as searchable and understandable as the digital world.

## 2025 crime datasets

This repository provides open, city-organized crime datasets for 2025. Files are grouped by country, city, and crime category, making them useful for research, public safety analysis, geographic analysis, urban studies, and world-modeling applications.

The regional export contains GeoJSON files with up to 1,500 records per city and crime category. Records are ordered with the newest 2025 dates first and include point geometry where available.

- [Browse regional datasets](data/README.md)
- [Machine-readable dataset index](data/DATASET_INDEX.json)

## Public fields

Each feature includes:

- `date`
- `year`
- `description`
- `metadescription`
- `address`
- `geometry`

Additional source attributes are flattened into ordinary top-level properties when available. The published files contain only 2025 records.

## License

Released under the [MIT License](LICENSE).
