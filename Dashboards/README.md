# Google Threat Intelligence Dashboards for Google SecOps SIEM

This directory contains predefined dashboards that enable security analysts to visualize and monitor Google Threat Intelligence data within Google SecOps SIEM.

## Overview

After collecting Google Threat Intelligence data into Google SecOps, these dashboards provide interactive visualizations for threat intelligence monitoring, indicator analysis, and correlation with events in your environment.

## Import a Dashboard

Follow these steps to import a dashboard into Google SecOps SIEM:

1. Log in to your Google SecOps instance.
2. In the navigation bar, click **Dashboards**.
3. Click **New dashboard** and then select **Import from JSON**. The Import dashboard confirmation dialog appears.
4. Click the **Upload dashboard files** button. The Select file dialog appears. Select the dashboard JSON file. The selected dashboard file will appear in the table.
![Import Dashboards](./Images/Import%20Dashboards.png)
5. Click **Import** to continue importing the dashboard to a personal or shared dashboard.

## Available Dashboards

| **Dashboard Name** | **File** | **Description** |
| --- | --- | --- |
| GTI Threat List | `GTI Threat Lists.json` | Threat lists are near real time loc lists that can be used to drive hunting/detection/blocking workflows. They are grouped into categories that can be used to target specific technologies/tech stacks/threats: ransomware, malicious network infrastructure, mobile, OS X, TOP + Trending locs, etc. |
| GTI Threat Intelligence | `GTI Threat Intelligence.json` | The Threat Intelligence Dashboard provides a high-level overview of ingested IoCs. Metrics are aggregated instantly by severity, entity type, and origin, allowing security teams to quickly prioritize and focus investigation efforts. |
| GTI Adversary Intelligence | `GTI Adversary Intelligence.json` | Provides context on IoC associations (Malware, Threat Actors, Campaigns, Reports) and allows drill-down based on GTI Threat Score and association type. |
---