# Day 17 - Vehicle Cost Analysis Dashboard

## Objective

The objective of Day 17 was to build a Vehicle Cost Analysis Dashboard using Claude and a CSV dataset. The dashboard analyzes fuel costs, maintenance expenses, environmental impact, E85 fuel economics, and vehicle ownership costs through interactive visualizations and KPI cards.

---

## Vehicle Information

| Parameter        | Value       |
| ---------------- | ----------- |
| Vehicle Model    | Hyundai i20 |
| Fuel Type        | Petrol      |
| Usage Type       | Mixed       |
| Monthly Distance | 1000 km     |
| Vehicle Age      | 3 Years     |

> Note: Replace the above details with your actual vehicle information.

---

## Dataset Used

* Downloaded the provided CSV dataset.
* Uploaded the dataset into Claude.
* Used the Vehicle Cost Analysis Dashboard prompt.
* Generated a complete HTML dashboard based on the dataset.

---

## Tasks Performed

### 1. Dataset Analysis

* Loaded the CSV file into Claude.
* Analyzed fuel consumption records.
* Evaluated maintenance costs.
* Computed environmental impact metrics.
* Calculated E85 fuel economics.

### 2. Dashboard Generation

Generated a responsive HTML dashboard containing:

* KPI Cards
* Fuel Cost Comparison
* Maintenance Cost Analysis
* CO₂ Emission Analysis
* E85 Economics Dashboard
* SVG Visualizations
* Fuel Type Comparison Cards
* Vehicle Age Analysis

### 3. Dashboard Testing

* Saved generated HTML file.
* Opened dashboard in browser.
* Verified responsiveness.
* Reviewed charts and calculations.

---

## Dashboard Features

### KPI Cards

The dashboard displayed:

* Cost per Kilometer
* E85 Cost per Kilometer
* E85 Premium vs Petrol
* Break-even Fuel Price
* Monthly Fuel Cost

### Visualizations

#### Cost per KM Bar Chart

Compares fuel costs across:

* Petrol
* Diesel
* CNG
* E85
* EV

#### CO₂ Emission Doughnut Chart

Shows environmental impact for each fuel type.

#### Cost vs Vehicle Age Chart

Analyzes ownership costs from:

* New Vehicle (0–2 years)
* Mid-Life Vehicle (3–5 years)
* Aged Vehicle (6–9 years)
* Old Vehicle (10+ years)

#### E85 Performance Gauge

Displays:

* E85 Score out of 10
* Fuel Cost Efficiency
* Environmental Benefits
* Refueling Convenience
* Maintenance Impact

---

## Key Findings

### Fuel Cost Analysis

* Different fuel types showed significant variations in operating costs.
* Cost per kilometer provides a more realistic ownership metric than fuel price alone.
* Monthly cost estimates help evaluate long-term expenses.

### Maintenance Analysis

* Vehicle age directly impacts maintenance costs.
* Older vehicles generally incur higher maintenance expenses.
* Preventive maintenance can reduce long-term ownership costs.

### Environmental Impact

* Fuel types vary significantly in CO₂ emissions.
* Alternative fuels may reduce environmental impact.
* Emission metrics help evaluate sustainability.

### E85 Economics

The dashboard calculated:

#### Pump Savings

Percentage savings at the fuel station compared to petrol.

#### Running Penalty

Additional fuel consumption cost due to lower mileage.

#### Break-Even Price

Maximum E85 fuel price that remains economically viable.

#### E85 Score

A composite score based on:

* Cost Efficiency
* Environmental Impact
* Refueling Convenience
* Maintenance Cost

---

## Screenshots

### Dashboard Overview

![Dashboard](dashboard-home.png)

### KPI Cards

![KPIs](kpi-cards.png)

### Cost Comparison Chart

![Cost Chart](cost-chart.png)

### CO₂ Emission Chart

![CO2 Chart](co2-chart.png)

### E85 Gauge

![Gauge](e85-gauge.png)

### Fuel Comparison Cards

![Fuel Cards](fuel-cards.png)

---

## Files Included

```text
Day17/
│
├── day17.md
├── vehicle_dashboard.html
├── dashboard-home.png
├── kpi-cards.png
├── cost-chart.png
├── co2-chart.png
├── e85-gauge.png
└── fuel-cards.png
```

## Key Learnings

### 1. Data-Driven Decision Making

Learned how raw CSV data can be transformed into actionable insights using dashboards.

### 2. Cost Analysis Techniques

Understood how to calculate:

* Cost per Kilometer
* Monthly Ownership Cost
* Maintenance Cost per Kilometer

### 3. Environmental Evaluation

Learned how CO₂ emissions can be visualized and compared across fuel types.

### 4. Dashboard Design Principles

Explored:

* KPI Cards
* SVG Visualizations
* Responsive Layouts
* Glassmorphism UI Design

### 5. Claude for Data Analytics

Discovered how Claude can:

* Analyze datasets
* Perform calculations
* Generate complete HTML dashboards
* Create interactive visualizations

---

## Conclusion

Day 17 demonstrated the power of combining AI-driven analytics with data visualization. By analyzing vehicle ownership costs, fuel efficiency, maintenance expenses, and environmental impact, I gained practical experience in transforming raw data into meaningful business insights. The generated HTML dashboard provided an effective way to visualize and compare vehicle operating costs while exploring the economics of E85 fuel.

---

## Git Commands Used

```bash
git add .
git commit -m "Completed Day 17 Vehicle Cost Analysis Dashboard"
git push origin main
```
