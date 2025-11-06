# Data Visualization Portfolio

A collection of dashboards, analytics projects, and visual explorations — designed to turn complex data into clarity. Each project emphasizes interactivity, performance, and storytelling through visuals.

---

## Featured Dashboards

### 1. Fleet Management Dashboard — *TFleet Logistics*
**Tech stack:** React, TypeScript, Recharts, FastAPI, PostgreSQL  
**Focus:** Real-time fleet performance and operational metrics  

**Highlights**
- Visualized truck utilization, delivery efficiency, and route performance.
- Integrated WebSocket streams for live vehicle tracking and delivery updates.
- Optimized Recharts performance using `PureComponent` and virtualized rendering.
- Built reusable chart components (line, bar, area) with type-safe data models.

**Built With**
- **React + TypeScript:** strongly typed dashboard components and API hooks.  
- **Recharts.js:** custom tooltips, gradient fills, and adaptive axis scaling.  
- **FastAPI:** backend REST API serving metrics from a PostgreSQL data warehouse.  
- **Caching Layer:** Redis for pre-aggregated daily stats to keep chart load times under 100ms.  

[🔗 View Live Demo](https://example.com/tfleet-dashboard)  
[📂 View Source](https://github.com/yourusername/tfleet-dashboard)

---

## Exploratory Data Projects

### • Covid19 Tracker (1965–2023)
**Dataset:** BP Statistical Review  
**Goal:** Visualize energy source transitions over six decades  
**Result:** Layered area chart with cumulative energy mix and source proportions.

[🔗 View Notebook](https://example.com/global-energy)

---

### • Data Dashboard Template
**Dataset:** Crunchbase API, custom scrapers  
**Goal:** Map VC funding distribution across African regions  
**Result:** Interactive chloropleth map using Plotly + Mapbox with tooltip drilldowns.

[🔗 Open Visualization](https://example.com/funding-map)

---

## 🧩 Tools & Techniques

**Visualization Libraries:** Recharts, D3.js
**Data Processing:** Pandas, SQL  
**Frontend Frameworks:** React, Next.js, Framer Motion  

---

> “Data visualization is not about decoration — it’s about compression. The right chart can replace a thousand words.”

