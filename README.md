# Qatar Air Quality Digital Twin — Art of the Possible

A sample demonstration of an air quality digital twin for Qatar: See, Understand, Predict, Test, Act.

---

## Data sources

| Source | Endpoint | Underlying dataset | Licence |
|---|---|---|---|
| Open-Meteo Air Quality API | `air-quality-api.open-meteo.com/v1/air-quality` | Copernicus Atmosphere Monitoring Service, ~40 km grid, 4 runs daily | CC BY 4.0 |
| Open-Meteo Forecast API | `api.open-meteo.com/v1/forecast` | ECMWF IFS and national models | CC BY 4.0 |
| CARTO basemaps | `basemaps.cartocdn.com` | OpenStreetMap data, CARTO cartography | ODbL 1.0 / CC BY 3.0 |
| OpenStreetMap tiles | `tile.openstreetmap.org` | OSM community survey | ODbL 1.0 |
| Esri World Imagery | `server.arcgisonline.com/.../World_Imagery` | Maxar, Earthstar, CNES/Airbus | Esri terms |
| Leaflet 1.9.4 | `unpkg.com/leaflet@1.9.4` | — | BSD 2-Clause |
| WHO Guidelines 2021 | ISBN 978-92-4-003422-8 | Global air quality guidelines | Published |
| Sample dataset | held in file | Constructed for demonstration | Illustrative only |

## Cadastral mapping

Not used. Street maps show roads, building footprints and place names — none of
which is a legal land parcel.

Qatari parcel geometry sits with the Ministry of Municipality, Survey and Land
Registration Department, and the Centre for Geographic Information Systems
(gisportal.gov.qa). Neither publishes it openly.

It would be required for plot-level work — siting a school, assessing a named
development, enforcing conditions on a specific site.

## Assumptions

32 in seven groups: places and geography, what the pollution is made of, time and
weather, people, forecasting, testing changes, thresholds and targets.

Each is tagged, described plainly, and given its numeric value where one exists.

## Quick start

Download `index.html` and open it in Chrome or Edge. No install, no server.

---

*Sample demonstration. Not for official, regulatory or compliance use.*
