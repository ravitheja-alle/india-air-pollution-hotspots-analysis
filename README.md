# 🌏 India Air Pollution Hotspots — Nationwide Snapshot (11 Nov 2025)

### 📊 Project Summary
This project analyzes India’s nationwide air-quality snapshot using CPCB (Central Pollution Control Board) station data from 11 Nov 2025.  
It identifies the most polluted cities, dominant pollutants, and regional clusters through data cleaning, aggregation, and visualization.

---

### 🎯 Objectives
- Aggregate pollutant readings from 500+ stations into state- and city-level insights.  
- Identify the **Top 10 most polluted stations** and **Top 10 polluted states**.  
- Visualize nationwide air-pollution intensity on an interactive geographic heatmap.  
- Communicate findings clearly for data-driven policy awareness.

---

### 🧰 Tools & Libraries
| Purpose | Tools |
|----------|-------|
| Data Cleaning | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn`, `plotly` |
| Geospatial | `plotly.express (density_mapbox)` |
| Environment | Jupyter Notebook / VS Code |

---

### 📈 Key Insights
1. **Delhi NCR dominates** the pollution chart — 9 of the top 10 stations are located within Delhi or Gurugram, led by IGI Airport (T3).  
2. **Particulate matter (PM₂.₅ and PM₁₀)** is the primary pollutant for ~85 % of stations nationwide.  
3. **Northern and central states** (Delhi, Haryana, UP, Rajasthan) record 2–3× higher average pollution levels compared with coastal or southern states.  

---

### 🗺️ Visuals
| Type | Description |
|------|--------------|
| [🌐 Interactive Map](Visuals/india_aqi_map_enhanced.html) | Explore India’s air-pollution intensity interactively. |

---

### ⚙️ How to Reproduce
1. Clone this repository  
   ```bash
   git clone https://github.com/Ravithejaalle/India_AQI_Hotspots_Analysis.git
   cd India_AQI_Hotspots_Analysis

2. Install dependencies

    pip install -r requirements.txt


3. Run the notebook

    jupyter notebook analysis.ipynb
