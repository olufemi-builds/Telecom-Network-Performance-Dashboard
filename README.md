# Telecom Network Performance Dashboard

## Project Overview

This project presents a telecom network analytics dashboard built in Power BI.

It analyzes 1000 rows of network performance data including uptime, downtime, faults, traffic load, and regional distribution.

The goal is to identify weak network areas and monitor infrastructure performance.

---

## Dashboard Preview

![Dashboard Preview](assets/dashboard-mockup.png)

---

## Business Problem

Telecom networks generate large operational data but lack clear visibility into:

- Regional performance issues
- Fault frequency patterns
- Traffic impact on uptime
- Underperforming sites

This dashboard solves that by centralizing key metrics into a single view.

---

## Dashboard Design

### KPI Layer (Top Section)

- Network Uptime %
- Total Downtime
- Total Faults
- Average Traffic Load
- Active Sites

---

### Analytical Layer (Middle Section)

- Uptime Trend Line Chart over time
- Fault Distribution by Region (Bar Chart)
- Traffic Load Pattern (Area Chart)

---

### Insight Layer (Bottom Section)

- Worst Performing Sites Table
- Region vs Network Type Heatmap

---

### Filter Panel

- Region
- Network Type
- Date Range

---

## Dataset Structure

Single table model:

- Date
- SiteID
- Region
- Network Type (3G, 4G, 5G)
- Uptime %
- Downtime
- Faults
- Traffic Load

---

## Key Metrics

- Uptime indicates service stability
- Downtime shows outage impact
- Faults measure network failures
- Traffic shows load pressure
- Site analysis identifies weak infrastructure

---

## Tools Used

- Power BI Desktop
- DAX
- Excel / CSV dataset

---

## Insights Generated

- Certain regions show higher fault rates
- Traffic spikes reduce uptime performance
- Some sites consistently underperform
- Network type affects reliability

---

## Project Outcome

This dashboard provides a structured view of telecom network health and supports faster operational decisions.

---

## Author
Olufemi Olamoyegun
