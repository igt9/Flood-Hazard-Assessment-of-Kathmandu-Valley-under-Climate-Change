# Flood Hazard Assessment of Kathmandu Valley under Climate Change Scenarios

## Overview
Flooding in the Kathmandu Valley has become increasingly severe due to rapid urbanization, river encroachment, inadequate drainage systems, and the impacts of climate change. This project assesses present and future flood hazards in the Kathmandu Valley using a **Rain-on-Grid (RoG) based 2D flood modeling approach** combined with **CMIP6 climate projections**.

The study integrates hydrodynamic flood modeling using **HEC-RAS 2D**, future climate projections under **SSP245 and SSP585 scenarios**, bias-corrected precipitation data, and spatial analysis to identify flood inundation, hazard zones, and high-risk areas.

---

## Study Area
The study focuses on the **Kathmandu Valley**, located in central Nepal, within the Upper Bagmati River Basin. Major rivers and tributaries such as the Bagmati, Bishnumati, Dhobikhola, Manohara, Hanumante, Balkhu, and Nakkhu were considered.

<img width="922" height="1193" alt="image" src="https://github.com/user-attachments/assets/b04ae67f-773f-4210-8a15-84b02b6a840f" />

---

## Methodology
The project follows a structured workflow combining data preparation, hydrodynamic modeling, climate projection, and spatial analysis.

### Key Methodological Components
- **Digital Elevation Model (DEM):** AW3D / ALOS-based terrain data  
- **Land Use/Land Cover (LULC):** Satellite-derived land cover maps  
- **Soil Data:** Hydrologic soil groups for infiltration modeling  
- **Hydrological Modeling:** Rain-on-Grid (RoG) approach in HEC-RAS 2D  
- **Climate Projections:** CMIP6 GCM data under SSP245 and SSP585  
- **Bias Correction:** Quantile Mapping (QM) applied to precipitation data  
- **Return Period Analysis:** 50-year and 100-year flood events  



<img width="938" height="910" alt="image" src="https://github.com/user-attachments/assets/be8e30e3-5bd3-44e2-9cef-1ef793c2f66f" />
  

---

## Climate Data Processing Tool
A **web-based climate data processing application** was developed as part of this project to automate the extraction and preparation of climate model data.

### Features
- Selection of station locations (latitude/longitude)
- Choice of climate scenario (Historical, SSP245, SSP585)
- Selection of CMIP6 climate models
- Custom date range selection
- Automatic conversion of precipitation data to mm/day
- Export of daily precipitation data in Excel/CSV format


---

## Model Calibration and Validation
The HEC-RAS 2D model was calibrated and validated using observed discharge data from the **Khokana hydrological station**. Model performance was evaluated using statistical indicators such as correlation coefficients and efficiency metrics.

<img width="915" height="608" alt="image" src="https://github.com/user-attachments/assets/2c8d9459-a6be-435a-b84c-3d8dc879fa29" />

<img width="915" height="551" alt="image" src="https://github.com/user-attachments/assets/5f570099-bb80-4c4c-ae55-8860547d6f08" />

<img width="891" height="532" alt="image" src="https://github.com/user-attachments/assets/0998a92f-55b7-453f-af3d-9ef4ce4d4775" />

<img width="921" height="505" alt="image" src="https://github.com/user-attachments/assets/1df79f6e-c65d-4965-a98c-7bf50c6b76a2" />







## Results and Discussion

### Flood Inundation Mapping
Flood inundation extents were generated for present and future climates under different return periods. Results show a strong relationship between increased rainfall intensity and inundation area.

### Flood Hazard Mapping
Flood hazard maps were developed using depth–velocity thresholds to classify hazard levels across the valley.

### Climate Change Impacts
- **SSP245:** Consistent increase in rainfall and flood risk toward the far future  
- **SSP585:** Intense near-future flooding followed by long-term variability  

<img width="692" height="637" alt="image" src="https://github.com/user-attachments/assets/7fcbc55e-1f04-4c85-ba9e-f506d1f06a81" />


## Key Findings
- Rain-on-Grid modeling effectively captures urban flood dynamics
- Climate change significantly increases flood hazard in low-lying areas
- Inundation area increases with rainfall intensity and return period
- Several urban zones within Kathmandu Valley are identified as **flood risk hotspots**

---

## Limitations
- Limited availability of high-resolution rainfall and discharge data
- Drainage and sewer networks not explicitly modeled
- Sediment transport processes not considered
- Uncertainty inherent in climate projections and downscaling methods

---

## Conclusion
This study demonstrates that integrating **2D Rain-on-Grid flood modeling** with **CMIP6 climate projections** provides a robust framework for assessing present and future flood hazards in urban basins. The results highlight the urgency of climate-adaptive flood management strategies for the Kathmandu Valley.

---


**Supervisor:** Prof. Dr. Prem Chandra Jha  
Department of Civil Engineering, Pulchowk Campus, Tribhuvan University
