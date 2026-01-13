# EV Power: Relationship Between EV Registrations and Clean Energy Sources (2023)

## Overview
This project investigates the geographical correlation between **Electric Vehicle (EV) registrations** and **clean energy consumption** across the United States in 2023. The core research question is: 
> *"In 2023, are EV registrations concentrated in states with cleaner energy sources?"*

By matching each state's renewable energy share with its EV registration count, this project reveals the distribution of green energy transition and reflects regional optimism toward electric vehicles.

## Data & Methodology

### Data Sources
- **Total Energy Use by State and Year (2023)**: Provides detailed energy consumption by source for each U.S. state.
- **EV Registrations by State (2023)**: Contains the approximate number of registered electric vehicles per state.

### Metrics & Calculation
The primary metric used is the **Renewable Energy Share per State**, defined as:
$$\text{Renewable Energy Share}_i = \frac{\text{Renewable Energy Use}_i}{\text{Total Energy Use}_i}$$

### Technical Stack
- [cite_start]**Language**: R [cite: 8, 45, 81, 119]
- **Libraries**: `tidyverse`, `sf` (for spatial data), `ggplot2`, `dplyr`, `rnaturalearth`, `data.table`.

## Analysis & Visualizations

### 1. Bivariate Geographical Mapping
I created a bivariate map where:
- **Warmer color fills** represent higher renewable energy shares.
- **Darker opacity/tone** indicates a higher volume of EV registrations.

> <img width="1049" height="756" alt="image" src="https://github.com/user-attachments/assets/7c4c271f-5da8-432b-aa20-a74e455f8dec" />

> *Caption: 2023 Landscape of Renewable Energy Share vs. EV Registrations.*

### 2. Regional Insights
- **The West Coast (e.g., California)**: Exhibits both a high renewable share and an extremely high number of EV registrations. This aligns with long-standing environmental policies and strong EV incentives.
- **Northern Central States (e.g., North Dakota, Wyoming)**: Show cool tones with pale opacity, indicating low renewable power consumption and low EV registration, reflecting a conservative attitude towards clean sources.
- **Pacific Northwest & New England**: Exhibit moderate-to-high renewable shares but relatively lower EV registration intensity, possibly due to population density and infrastructure availability.

## Academic Integrity & Honor Code
**Note on Code Availability:**
In accordance with the **UC Berkeley Honor Code** and to maintain academic integrity for the course (Lab 4 Project), the source code for data cleaning and map generation is **not publicly available** in this repository to prevent plagiarism. 

## Contact
- **Author**: Hex Wu
- **Email**: [hex@berkeley.edu](mailto:hex@berkeley.edu)
- **Portfolio**: [hexVerse Portfolio](https://hexverse.framer.media)
