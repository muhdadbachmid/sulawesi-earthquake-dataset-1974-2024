# Sulawesi Earthquake Dataset (1974–2024) - USGS

This repository contains a comprehensive dataset detailing earthquake activity in the **Sulawesi region of Indonesia and its surrounding areas**, spanning 50 years. All data is sourced from the **United States Geological Survey (USGS)**.

## About the Dataset

This dataset provides a detailed record of seismic events, crucial for understanding the seismicity, tectonic dynamics, and seismic hazard assessment in this highly active seismic zone.

### Data Source

All earthquake data is directly obtained from the [USGS Earthquake Catalog](https://earthquake.usgs.gov/).

### Spatial and Temporal Coverage

The dataset includes earthquakes with a **magnitude of 2.5 and above** within the following geographical and temporal bounds:

* **Time Period:** January 1st, 1974 – July 1st, 2024
* **Geographic Region (Sulawesi):**
    * **Latitude**: -6.184 to 2.021
    * **Longitude**: 118.433 to 125.552

## Dataset Structure (CSV File: `sulawesi_earthquakes_1974_2024_usgs.csv`)

The primary data file is `sulawesi_earthquakes_1974_2024_usgs.csv`. Each row represents a single earthquake event and includes the following columns (as typically provided by USGS):

| Column           | Data Type | Description                                                              |
| :--------------- | :-------- | :----------------------------------------------------------------------- |
| `time`           | Datetime  | Coordinated Universal Time (UTC) of the earthquake event.                |
| `latitude`       | Float     | Geographic latitude of the earthquake's epicenter.                       |
| `longitude`      | Float     | Geographic longitude of the earthquake's epicenter.                      |
| `depth`          | Float     | Depth of the earthquake's hypocenter in kilometers (km).                 |
| `mag`            | Float     | Magnitude of the earthquake.                                             |
| `magType`        | String    | Type of magnitude scale used (e.g., `mb`, `Mww`, `Mw`, `ML`).            |
| `nst`            | Integer   | The total number of seismic stations used to determine the event's location. |
| `gap`            | Float     | The largest azimuthal gap in degrees between stations.                   |
| `dmin`           | Float     | Horizontal distance from the epicenter to the nearest station (in degrees). |
| `rms`            | Float     | The root-mean-square (RMS) travel time residual in seconds.             |
| `net`            | String    | The ID of the network that originally reported the event.                |
| `id`             | String    | A unique identifier for the earthquake event.                            |
| `updated`        | Datetime  | The last time the event's information was updated (UTC).                 |
| `place`          | String    | Textual description of the event's location.                             |
| `type`           | String    | Type of seismic event (e.g., `earthquake`).                            |
| `status`         | String    | Status of the event (`reviewed`, `automatic`).                           |
| `locationSource` | String    | The network or agency that determined the event's location.              |
| `magSource`      | String    | The network or agency that determined the event's magnitude.             |

## Potential Uses and Analysis

This dataset is highly suitable for various applications, including:

* **Seismicity Analysis:** Studying earthquake frequency, magnitude distribution, and spatial patterns in Sulawesi.
* **Seismic Hazard Assessment:** Informing urban planning and risk mitigation strategies.
* **Geological and Tectonic Research:** Investigating complex fault systems and subduction zones in the region.
* **Time Series Analysis:** Analyzing temporal trends and recurrence intervals of earthquakes.
* **Machine Learning / Deep Learning:** Developing predictive models for seismic events.

## Usage in Research

This dataset was specifically used in the following study:

**"Attention-based Residual Long Short-Term Memory for Earthquake Return Period Prediction in the Sulawesi Region"**

* **Published in:** *Jurnal Ilmu Komputer dan Informasi (JIKI)*, Vol. 18(2), June 2025.


