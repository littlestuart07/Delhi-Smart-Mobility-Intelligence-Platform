# 🚦 Delhi Smart Mobility Intelligence Platform

**An end-to-end Business Intelligence project analyzing Delhi's urban mobility ecosystem** — integrating public transit, traffic, weather, and demographic data into a single Power BI analytics environment.

---

## 📌 Overview

The **Delhi Smart Mobility Intelligence Platform** brings together multimodal transportation data — bus GTFS, metro GTFS, bike-share, live traffic conditions, weather, and demographics — to give city planners, transport authorities, and analysts a unified, data-driven view of how the city moves.

Built primarily in **Power BI**, the dashboard turns raw, siloed datasets into interactive visual analytics: route coverage, traffic performance, weather impact, and city-wide mobility health — all in one place.

---

## 🎯 Objectives

- Integrate multimodal transportation datasets into one analytics layer
- Analyze traffic and transit performance across the city
- Monitor weather impact on mobility and commute conditions
- Visualize metro, bus, and bike-share network coverage
- Generate executive-level mobility insights for decision-makers
- Support data-driven urban transportation planning

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `Delhi.pbix` | Main Power BI dashboard file — all reports and visuals |
| `Delhi GTFS.zip` | Delhi Bus GTFS feed (routes, trips, stops, schedules) |
| `DMRC_GTFS.zip` | Delhi Metro (DMRC) GTFS feed |
| `Bike-Sharing.zip` | Bike-share / micromobility trip and station data |
| `Delhi Traffic Dataset.zip` | Raw traffic dataset (speed, density, road type, travel time) |
| `delhi_traffic_features.csv` | Processed traffic feature set used for analysis |
| `delhi_traffic_target.csv` | Target/label data for traffic modeling |
| `Delhi_Weather_2025.csv` | 2025 daily weather data (temperature, humidity, rainfall, wind speed) |
| `Delhi_Demographics.xlsx` | Population and urban demographic indicators |
| `kpi_Urban-Pulse.pptx` | KPI summary deck for the Urban Pulse platform |

---

## 🗂️ Datasets Used

### 🚌 Public Transport (GTFS)
- Delhi Bus GTFS
- Delhi Metro (DMRC) GTFS

**Core files:** `routes.txt` · `trips.txt` · `stops.txt` · `stop_times.txt` · `agency.txt` · `calendar.txt` · `shapes.txt`

### 🚲 Bike-Share / Micromobility
- Station-level trip and availability data

### 🚗 Traffic Dataset
- Average Speed · Distance · Road Type · Traffic Density · Travel Time · Weather Condition

### 🌦️ Weather Dataset (2025)
- Max / Min / Average Temperature · Humidity · Rainfall · Wind Speed

### 👥 Demographic Dataset
- Population statistics
- Urban indicators

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — dashboarding and visualization
- **DAX** — calculated metrics and KPIs
- **Power Query** — data transformation and cleaning
- **Python** — data preprocessing
- **GTFS** — standard transit data format
- **Open-Meteo API** — weather data source

---

## 📊 Dashboard Pages

**1. Executive Dashboard** — KPIs, weather overview, demographic insights

**2. Traffic Analytics** — traffic density, average speed, road type, weather impact on traffic

**3. Public Transport Analytics** — route distribution, service analysis, bus network insights

**4. Smart Mobility Dashboard** — bus stop map, metro station map, bus vs. metro comparison, transport network KPIs

**5. Executive Intelligence Dashboard** — mobility health score, traffic performance, weather analytics, executive insights

---

## ✨ Key Features

- Interactive Power BI dashboards across 5 dedicated pages
- Geospatial mapping of bus stops and metro stations
- City-wide Mobility Health Score
- Weather impact analysis on traffic and transit
- Transit performance and route-level monitoring
- Executive-ready KPI summaries

---

## 📈 Key Metrics

- Total Routes · Total Stops · Total Trips
- Average Speed
- Average Temperature · Average Humidity
- Mobility Health Score

---

## 💼 Business Impact

This platform helps:

- **Transport Authorities** — monitor and optimize service performance
- **Urban Planners** — identify infrastructure gaps and plan improvements
- **Smart City Teams** — track city-wide mobility health
- **Government Agencies** — make informed, data-backed transportation policy decisions

---

## 👤 Author

**Suyash Agrawaal**
