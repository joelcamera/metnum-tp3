# Metodos Numéricos

## TP 3 - Predicción de Temperatura con Cuadrados Mínimos

Descomprimir los csv con:

```
bunzip2 data/CitiesEastChunk.csv.bz2
bunzip2 data/CitiesWestChunk.csv.bz2
```

Los mismos se armaron usando PostgreSQL y la data de la catedra
junto con la de https://github.com/bahar/WorldCityLocations.

Además de pandas usamos `geopandas` para el mapa.

Cada sección tiene un ipynb asociado:

* Temperatura global -> "world temperature.ipynb"
* Temperatura con países -> "temperature by countries.ipynb"
* Temperatura por ciudades -> "El Paso vs Cleveland.ipynb"
