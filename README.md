# Splunk SSH Brute-Force Detection Dashboard

## Overview
Built an interactive Splunk dashboard to monitor SSH authentication logs, visualize failed login attempts, identify brute-force patterns, and map attack origins via geo-visualization using SPL queries and choropleth mapping. Demonstrates cross-platform SIEM proficiency (Sentinel/KQL and Splunk/SPL).

## Objective
SSH brute-force attacks remain one of the most common initial access vectors observed in the wild, mapping to MITRE ATT&CK technique T1110 (Brute Force). This project simulates a SOC analyst workflow: ingesting authentication logs, detecting repeated failed login attempts, identifying likely brute-force sources, and visualizing attack origin geography to support triage and response decisions.

## Environment
- **Platform:** Splunk Cloud (free trial)
- **Data source:** Synthetic SSH authentication logs (auth.log format)
- **Ingestion method:** Manual file upload

## Architecture
`[TO ADD: simple diagram or description — e.g. Synthetic auth.log → Splunk Cloud (Add Data upload) → SPL search & stats → Dashboard panels (table, timechart, choropleth map)]`

## Detection Logic
`[TO ADD once SPL is built: failed login search, brute-force threshold logic, time window used, why that threshold was chosen]`

## Geo-Visualization
`[TO ADD: iplocation command usage, choropleth map panel, what it reveals for triage]`

## MITRE ATT&CK Mapping
- **T1110 — Brute Force**

## Skills Demonstrated
- SPL query development (stats, timechart, iplocation)
- Splunk dashboard design (panels, choropleth mapping)
- SIEM log analysis and detection engineering
- Cross-platform SIEM proficiency (Sentinel/KQL ↔ Splunk/SPL)

## Screenshots
`[TO ADD: dashboard overview, failed logins panel, geo-map panel]`

## Repository Structure
```
├── spl-queries/          # SPL search queries used in the dashboard
├── dashboard-export/     # Exported dashboard XML
├── sample-data/          # Synthetic SSH auth log sample
├── screenshots/          # Dashboard screenshots
└── docs/                 # Methodology and detection reasoning
```
