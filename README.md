# Formula 1 Data Analysis Project

## Overview  

<p>
  <img
    src="https://github.com/user-attachments/assets/70c117ce-3f9f-43ac-bb1b-df4f90744f28"
    alt="Team with Prof Anna Leach"
    align="right"
    width="350"
  />
  A comprehensive exploration of Formula 1 racing data using the **f1dataR** package in R. We used live datasets from 2021 to 2023 and a few races from 2024. This repository ingests lap times, telemetry streams (including speed, throttle, and brake), pit-stop logs, and race results to uncover actionable performance insights for drivers and teams across various circuits. Detailed methodology, visualizations, and key findings are documented in the accompanying project write-up.
</p>


---
## Key Features  
- **Lap-by-Lap Performance**  
  Analyze sector times, stint consistency, and overall pace.  
- **Telemetry Visualization**  
  Plot speed, throttle, brake, and DRS usage over each lap.  
- **Pit-Stop Strategy**  
  Compare stop timing, duration, and impact on race position.  
- **Circuit Benchmarking**  
  Contrast driver and team performances track-by-track.  
---
## Findings  
- **Lap-Time Consistency**  
  Certain teams (e.g., Red Bull) demonstrated a pace advantage of up to 0.2 s per lap over their closest rivals.  
- **Pit-Stop Strategy Impact**  
  Under-cut strategies yielded an average net gain of ~1.5 s, especially on circuits with shorter pit-lane transit times.  
- **Tire Degradation Trends**  
  Lap times increased by ~0.15 s per lap after 15 laps, underscoring optimal stint length.  
- **Telemetry Insights**  
  Each 1 % increase in throttle application on corner exits correlated with a ~0.05 s lap-time improvement.  
- **Circuit-Specific Performance**  
  High-speed tracks favored low-drag setups, while twistier circuits rewarded downforce and cornering stability.  

(See full methodology and results in the attachments >> project write-up.)

---
## Technologies Used  
- **R**  
- **f1dataR** for data ingestion (laps, telemetry, pit stops, results)  
- **tidyverse** (dplyr, tidyr, ggplot2) for data wrangling and static plots  
- **plotly** for interactive visualizations  
- **R Markdown** for reproducible reporting  
---
## Data Sources  
All data, lap times, telemetry streams, pit-stop logs, and race results were sourced using the `f1dataR` package.  
