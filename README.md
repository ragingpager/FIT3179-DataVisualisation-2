# Victoria's Water Story: Rainfall & Reservoir Storage (2010-2025)

**Author:** Rahul Pejathaya (32993226)
**Course:** FIT3179 Data Visualisation 2, Monash University
**Date:** October 2025

---

## Project Overview

An interactive data visualization exploring the relationship between rainfall patterns and water storage across Victoria, Australia from 2010 to 2025. This project reveals a critical 3-4 month lag between precipitation and reservoir replenishment, geographic disparities in water distribution, and the complex dynamics of Victoria's water infrastructure.

**Live Demo:** [View Visualization](https://ragingpager.github.io/FIT3179-DataVisualisation-2/)

---

## Visualizations

This project includes five interactive visualizations:

1. **Geographic Map** - Rainfall distribution across 28 monitoring stations in Victoria
2. **Seasonal Heatmap** - 190 months of rainfall patterns by year and month
3. **System Storage Area Chart** - Stacked view of 17 reservoir systems over time
4. **Capacity Paradox Bubble Chart** - Reservoir size vs. storage levels
5. **Rainfall vs Storage Dual-Axis** - Temporal analysis showing 3-4 month lag

---

## Key Insights

- **Geographic Divide:** Coastal areas receive significantly more rainfall than inland regions
- **3-4 Month Lag:** Storage responds to rainfall with an observable delay
- **Capacity Paradox:** Large reservoirs don't guarantee water security
- **Seasonal Variability:** Winter brings reliable rainfall, spring shows dramatic variation

---

## Technologies Used

- **Vega-Lite 5** - Declarative visualization grammar
- **HTML5/CSS3** - Structure and styling
- **Tailwind CSS** - Utility-first CSS framework
- **Google Fonts** - Poppins and Source Sans 3
- **GitHub Pages** - Hosting

---

## Data Sources

**Rainfall Data:**
[Bureau of Meteorology (BOM) - HQ Monthly PRCP dataset](http://www.bom.gov.au/climate/data/index.shtml)
28 rainfall stations across Victoria, 2010-2025

**Storage Data:**
[Southern and Western Victoria water storage levels - monthly dataset](https://www.water.vic.gov.au/our-programs/water-monitoring-and-reporting/current-water-snapshot)
66 reservoirs across 17 systems, 2010-2025

**Population Data:**
[Australian Bureau of Statistics (ABS)](https://www.abs.gov.au/statistics/people/population/national-state-and-territory-population/latest-release)

---

## Design Principles

- **What/Why/How Framework:** Follows Munzer's analytical framework
- **Five Design Sheets:** Iterative design methodology applied
- **Color Consistency:** Blue for rainfall, green for storage
- **Typography:** Clear hierarchy with Poppins and Source Sans 3
- **Layout:** Grid-based responsive design
- **Storytelling:** Guided narrative with annotations and insights
- **Data-Ink Ratio:** Minimalist design maximizing information density

---

## Interactive Features

- **Filters:** Year/month sliders, system selectors, date ranges
- **Tooltips:** Detailed information on hover
- **Annotations:** Dynamic min/max markers with color-matched labels
- **Responsive:** Adapts to different screen sizes
- **Checkboxes:** Toggle visibility of rainfall/storage series

---

## Local Development

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/ragingpager/FIT3179-DataVisualisation-2.git
```

2. Navigate to the project directory:
```bash
cd FIT3179-DataVisualisation-2
```

3. Open with a local server (required for loading external data):
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

4. Open browser to `http://localhost:8000`

---

## License

This project is submitted as academic work for FIT3179 at Monash University.
Data sources retain their original licenses and attributions.

---

## Acknowledgments

- Bureau of Meteorology for rainfall data
- Water Victoria for reservoir storage data
- FIT3179 teaching team for guidance and feedback
- Vega-Lite community for excellent documentation

---

**Note:** This visualization was created as part of academic coursework. All data sources are properly attributed and publicly available.
