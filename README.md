# karta-uz

Файлы данных для приложения «Карта» — карта Узбекистана.

Здесь лежат только открытые данные, в разделе [Releases](../../releases):

| Файл | Что это |
|---|---|
| `uzbekistan.pmtiles` | векторная карта Узбекистана (формат PMTiles): приложение читает её онлайн кусками или скачивает для офлайна |
| `roads.bin.gz` | граф дорог для офлайн-маршрутов на машине и пешком |
| `search.tsv.gz` | база поиска: города, улицы, адреса, заведения |
| `manifest.json` | размеры и SHA-256 файлов |

## Источники и лицензия

- Данные карты © участники [OpenStreetMap](https://www.openstreetmap.org/copyright), лицензия [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
- Тайлы вырезаны из сборки [Protomaps Basemap](https://protomaps.com) (данные OpenStreetMap).
- Граф дорог и база поиска построены из выгрузки OpenStreetMap ([Geofabrik](https://download.geofabrik.de/asia/uzbekistan.html)).

Эти файлы — производная база данных OpenStreetMap и распространяются на условиях ODbL 1.0.
