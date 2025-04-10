# The Pulse of Progress: Automating KPI Alerts for Data-Driven Decisions

This project provides a Python-based solution for automating Key Performance Indicator (KPI) alerts, enabling businesses to proactively monitor their operational health and make timely, data-driven decisions.

## Description

In today's fast-paced business environment, simply tracking numbers on dashboards isn't enough. True competitive advantage comes from understanding the *implications* of those numbers in real-time and acting decisively. This requires more than reactive analysis; it demands **proactive insights**.

This project delivers precisely that by automating KPI alerts.

* **Key Performance Indicators (KPIs):** These are the vital signs of a business, reflecting its ability to navigate market changes and achieve strategic goals.
* **Automated KPI Alerts:** This system acts as an early warning system, signaling potential opportunities or risks as they emerge.

By automating alerts, we move from reactive analysis to proactive risk management and opportunity identification. This allows for a deeper connection between granular operational data and broader trends, leading to more informed and timely strategic decisions.

## Key Alerting Features

The system provides detailed and actionable alerts, including:

* **KPI Value:** The current value of the monitored KPI.
* **Change Magnitude and Direction:** The extent and direction of change (e.g., "15% drop in weekly sales").
* **Historical Comparison:** Comparison to previous periods (daily, weekly, monthly averages) to provide context.
* **Potential Contributing Factors (Optional):** Integration with other data sources can provide insights into possible causes of changes.
* **Links to Further Information:** Direct links to dashboards or reports for in-depth analysis.

## KPIs Monitored

This project tracks the following KPIs:

* Total Number of Orders
* Gross Revenue
* Discount Amount
* Net Revenue
* Average Delivery Time of Orders
* Average Preparation Time of Orders
* Total Users
* New Users (within the specified time period)
* User Retention (within the specified time period)
* **Percentage Change:** Percentage change for all the above KPIs over the specified time period

## Data Sources

The project integrates with the following data sources:

* **Database:** MySQL
* **Cloud Storage:** Google Cloud Storage

## Data Access

Data is accessed using the following technologies:

* BigQuery
* MySQL Connector

## Alerting Module

The alerting module is built using Python and leverages the following:

* **Python:** Core logic and data manipulation.
* **Email:** For sending email notifications.
* **Requests:** For potential integration with other APIs or services.
* **Gmail:** Used for sending email alerts.


