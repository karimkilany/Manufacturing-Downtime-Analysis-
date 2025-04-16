#Manufacturing Downtime Analysis Dashboard project using Microsoft power pi 

## Overview

This project focuses on analyzing manufacturing production and downtime data to identify bottlenecks, understand performance trends, and derive actionable insights. It processes data related to line productivity, product specifications, downtime factors, and line downtime records, aiming to visualize key performance indicators (KPIs) and causes of inefficiency.

The analysis is based on a defined data structure, detailed in the [Data Dictionary] (#data-description).

## Features

* **Data Loading & Cleaning: ** Ingests data (e.g., from CSVs) based on the predefined schema, handles data types, and prepares it for analysis.
* **Downtime Analysis: ** Calculates total downtime per batch, identifies frequency and duration of different downtime factors.
* **Productivity Metrics: ** Calculates production times and potentially availability rates.
* **Root Cause Exploration: ** Analyzes contributions of specific factors (like operator errors) to downtime.
* **Visualization: ** Generates charts including:
    * Pareto analysis of downtime causes.
    * Time series trends for productivity and downtime.
    * Comparisons across products or other dimensions.

* **Interactive Dashboard: ** 
  
## Data Description

The analysis uses data structured across four main areas, as defined in the original data dictionary:

1.  **Line Productivity: ** Batch-level production details (Date, Product, Batch, Operator, Start/End Times).
2.  **Products: ** Product specifications (Product ID, Flavor, Size, Min Batch Time).
3.  **Downtime Factors: ** Definitions of downtime causes (Factor ID, Description, Operator Error flag).
4.  **Line Downtime: ** Downtime recorded per batch for various factors (Batch ID, Downtime Factor Columns).

## Technology Stack

* **Language: ** Microsoft power query
* **Core **
    * Microsoft Power Pi
    * Microsoft power Pi: Data visualization.
* **Dashboarding (If used): ** [Microsoft Power Pi]

