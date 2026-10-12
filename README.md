# Impact-of-Weather-on-U.S.-Shipment-Delays

# Impact of Weather on U.S. Shipment Delays

## Overview

This project investigates whether weather conditions are associated with shipment delays across selected U.S. states. The analysis combines logistics data from the DataCo SMART Supply Chain dataset with historical weather data obtained from Open-Meteo.

The project was developed as my M.S. Data Analytics capstone with a concentration in Data Engineering at Western Governors University.

## Business Question

**Do weather conditions have a statistically significant relationship with shipment delays?**

Understanding whether weather contributes to late deliveries can help organizations distinguish environmental causes of delays from operational factors and make better-informed decisions about logistics planning and supply-chain performance.

## Technologies

* Python
* Pandas
* NumPy
* SQLite
* SQL
* Power BI
* Open-Meteo historical weather data
* Jupyter Notebook
* Statistical analysis and hypothesis testing

## Data

The analysis incorporated shipment records and historical weather observations for eight U.S. states:

* California
* New York
* Texas
* Pennsylvania
* Washington
* Illinois
* Ohio
* Florida

Shipment data came from the **DataCo SMART Supply Chain dataset**, while historical weather observations were obtained from **Open-Meteo**.

The analysis covered shipments from **April through August 2016**.

## Data Engineering & Analysis

The project included:

1. Cleaning and preprocessing shipment data.
2. Retrieving historical weather observations.
3. Transforming and integrating logistics and weather datasets.
4. Storing structured data in SQLite.
5. Querying and analyzing the integrated dataset.
6. Examining relationships between weather variables and shipment delays.
7. Performing statistical hypothesis testing.
8. Developing an interactive Power BI dashboard to communicate results.

## Key Findings

Approximately **54.6% of the analyzed shipments were classified as late**.

Despite the relatively high late-delivery rate, correlations between the evaluated weather variables and shipment delays were near zero.

Statistical testing also did not identify a significant association between the evaluated weather conditions and late-delivery outcomes.

### Conclusion

The results did **not provide sufficient evidence that weather was a significant driver of shipment delays** within the analyzed data.

This finding is useful because a negative result is still actionable: it suggests that organizations investigating the high rate of late shipments should examine other factors, such as fulfillment operations, carrier performance, shipping method, routing, or other supply-chain processes.

## Power BI Dashboard

An interactive Power BI dashboard was developed to visualize:

* Overall shipment performance
* Late-delivery rates
* Geographic shipment patterns
* Weather conditions
* Relationships between weather variables and shipment outcomes

## Repository Structure

```text
├── data/          # Data documentation and permitted datasets
├── notebooks/     # Jupyter notebooks used for analysis
├── src/           # Python scripts
├── sql/           # SQL/database scripts
├── dashboard/     # Power BI dashboard or related files
├── images/        # Dashboard and visualization screenshots
├── requirements.txt
└── README.md
```

## Skills Demonstrated

This project demonstrates experience with:

* Data cleaning and transformation
* ETL and data integration
* API-based data acquisition
* Relational databases
* SQL
* Exploratory data analysis
* Statistical analysis
* Data visualization
* Power BI dashboard development
* Python-based data workflows
* Translating analytical results into business recommendations

## Author

**Tomeka Pena**

M.S. Data Analytics – Data Engineering
Western Governors University
