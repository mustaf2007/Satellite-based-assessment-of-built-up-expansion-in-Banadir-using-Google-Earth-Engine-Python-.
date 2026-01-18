# Mogadishu Urban Growth Analysis (2015–2025)

Satellite-based assessment of built-up expansion in Banadir using **Google Earth Engine + Python**.

## Overview

This project quantifies urban growth across all 18 districts of Mogadishu using Landsat time-series and NDBI change detection. Results are aggregated to official admin-2 boundaries and delivered through an interactive Folium dashboard.

## Key Findings

- **Daynile ~41.8 km²** – primary sprawl corridor  
- **Heliwa ~18.8 km²** – high flood exposure zone  
- **Dharkenley ~18.0 km²** – mixed residential expansion  
- Inner districts <1 km² – densification rather than horizontal growth

## Methods

1. Google Earth Engine processing  
   - Landsat 2015–2025  
   - NDBI computation  
   - Change thresholding

2. District aggregation  
   - GeoPandas integration  
   - Pixel-area to km² conversion

3. Visualization  
   - Folium interactive map  
   - District popups with statistics

## Outputs

- `outputs/Mogadishu_Urban_Growth_Final.html` – interactive map  
- `outputs/growth_by_district.csv` – statistics table

## Skills Demonstrated

- Earth Observation  
- GEE Python API  
- GeoPandas & Folium  
- Reproducible research  
- Development analytics

## How to Run

```bash
pip install -r requirements.txt
