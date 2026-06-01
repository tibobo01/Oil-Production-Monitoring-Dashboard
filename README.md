# Oil Production Monitoring Dashboard

https://acrobat.adobe.com/id/urn:aaid:sc:EU:8946daaf-e458-4b1c-bb1f-4c5ced2ad142

## Project Overview

This project focuses on cleaning, analyzing, and visualizing an oil well production dataset using Power BI. The dataset was intentionally designed with missing values, inconsistent records, and unrealistic operational measurements to simulate real-world data quality challenges commonly encountered in the oil and gas industry.

The objective was to transform the raw dataset into a reliable source of information and develop an interactive dashboard that provides insights into production performance, operational efficiency, downtime trends, and cost management across multiple oil fields and operators.

---

## Business Problem

Oil and gas companies rely on accurate operational data to make production and maintenance decisions. Poor data quality can lead to incorrect performance assessments, inaccurate forecasts, and inefficient resource allocation.

This project demonstrates how data cleaning, validation, and visualization techniques can be applied to improve data reliability and support operational decision-making.

---

## Dataset Description

The dataset contains operational records from oil wells owned by:

* Chevron
* NNPC
* Seplat
* TotalEnergies
* Oando
* ExxonMobil
* Shell

The data includes:

* Well Information
* Production Volume
* Pressure Measurements
* Temperature Readings
* Operating Costs
* Downtime Records
* Company and Field Information

---

## Data Cleaning Process

Several data quality issues were identified and addressed:

### Handling Missing Values

Missing values were not automatically removed because many affected records contained valuable information in other columns. Appropriate data cleaning strategies were applied to preserve data integrity while minimizing information loss.

### Correcting Invalid Temperature Values

The temperature column contained impossible values such as **−400°C**.

Using engineering principles:

* Absolute Zero = −273.15°C
* Temperatures below this limit are physically impossible

Invalid records were identified and corrected to ensure realistic operating conditions.

### Standardization of Operational Metrics

The following variables were standardized and validated using engineering and operational constraints:

* Pressure
* Production Rate
* Production Volume
* Operating Cost

### Feature Engineering

Additional helper columns were created, including:

* Downtime Categories
* Operational Status Indicators
* Performance Classification Metrics

---

## Dashboard Features

The Power BI dashboard provides:

### Executive KPIs

* Total Production Volume
* Average Production Rate
* Total Operating Cost
* Active Wells
* Downtime Statistics

### Production Analysis

* Production Trends Over Time
* Company Performance Comparison
* Field-Level Production Analysis

### Operational Performance

* Downtime Analysis
* Cost Monitoring
* Well Performance Tracking

### Interactive Filtering

Users can filter results by:

* Company
* Field
* Well
* Operational Status
* Time Period

---

## Key Insights

* Identified operational inefficiencies through downtime categorization.
* Revealed production differences across companies and fields.
* Improved data reliability by correcting invalid operational measurements.
* Enabled quick performance monitoring through interactive KPI dashboards.

---

## Tools & Technologies

* Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Intelligence

---

## Project Outcome

The project demonstrates the complete analytics workflow from data cleaning and validation to dashboard development and business insight generation. It highlights the importance of data quality in operational analytics and showcases how Power BI can be used to support decision-making in the oil and gas industry.
