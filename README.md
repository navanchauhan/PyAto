# PyAto
![PyPI - Version](https://img.shields.io/pypi/v/PyAto-navanchauhan.svg) ![PyPI - License](https://img.shields.io/pypi/l/PyAto-navanchauhan.svg) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/cbe32a93922141a693b9679229ffcfbd)](https://www.codacy.com/app/navanchauhan/PyAto?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=navanchauhan/PyAto&amp;utm_campaign=Badge_Grade)


A Python Wrapper for the Zomato API

### Initialisation
```
import PyAto
PyAto.setAPIKey("Your Key Here")
```
or
```
import PyAto as pyato
pyato.setAPIKey("Your Key Here")
```
### Functions

| Function | Required Values | Output |
|----------|-----------------|--------|
| getCategories | None | JSON |
| getCities | Name (String) | JSON |
| getCityID | Name (String) | Integer |
| getCollections | CityID (Integer) | JSON |
| getCuisines | CityID (Integer) | JSON |
| getGeocode | Latitude & Longitude | JSON |
| getEstabblishments | CityID | JSON |
