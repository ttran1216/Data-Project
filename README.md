# Theft and Loss of Controlled Substances: Malloy Data Analysis

## Background
This project analyzes a dataset related to the **theft and loss of controlled substances** (chemicals lost) within various business activities. The data captures detailed information on incidents of theft, including the quantity of chemicals lost, business activity types, and geographical information (such as state-level data). Understanding the patterns and key factors contributing to theft can help organizations better manage their inventory and implement more effective loss-prevention strategies.

The dataset includes:
- **State**: The state where the loss occurred.
- **Business Activity**: The type of business involved (e.g., pharmacy, distributor, manufacturer).
- **Quantity Lost**: The amount of chemicals lost, measured in milliliters, unit, milligram,...
- **Theft Count**: The number of theft incidents recorded.

## Motivation
The motivation for this analysis is to uncover trends and insights into the theft of controlled substances, a critical issue for businesses in the chemical and pharmaceutical industries. By understanding which states and business activities are more prone to theft and loss, businesses can implement targeted security measures, optimize inventory management, and reduce financial losses. This analysis aims to provide actionable insights to guide policy and decision-making processes within the industry.
## Code
This repository contains 1 Malloy code file:
- [`theft_loss.malloynb`](theft_loss.malloynb), performs the analysis piece of the theft and loss of controlled substances data provided by the Data Liberation Project.

## Summary of Findings
Based on the analysis of the dataset, the following key findings were observed:
<p>
<img alt="Images/Quantity loss by state." width="65%" 
  src="https://github.com/ttran1216/Data-Project/blob/main/Images/Quantity%20loss%20by%20state.png"><br>
<em>Figure: Screenshot of Quantity loss by state.</em></p>

- **States with the highest chemical loss**: States like **Texas** and **Illinois** showed the highest total quantity of chemicals lost. These states may face regional challenges that should be addressed with improved loss prevention measures.

<p>
<img alt="Images/Total quantity loss by business activities." width="65%" 
  src="https://github.com/ttran1216/Data-Project/blob/main/Images/Total%20quantity%20loss%20by%20business%20activities.png"><br>
<em>Figure: Screenshot of Total quantity loss by business activities.</em></p>

- **Business activities with the highest theft counts**: The **pharmacy** sector had the highest frequency of theft incidents, followed by **distributors** and **chemical manufacturers**.


<p>
<img alt="Images/Total theft by business activities." width="65%" 
  src="https://github.com/ttran1216/Data-Project/blob/main/Images/Total%20theft%20by%20business%20activities.png"><br>
<em>Figure: Screenshot of Total theft by business activites.</em></p>

- **Business activities with the highest chemical loss**: **Distributors** experienced the most significant quantity of chemicals lost, followed by **pharmacies** and **chemical exporters**.

<p>
<img alt="Images/Total quantity loss by loss type." width="65%" 
  src="https://github.com/ttran1216/Data-Project/blob/main/Images/Total%20quantity%20loss%20by%20loss%20type.png"><br>
<em>Figure: Screenshot of Total quantity loss by loss type.</em></p>

- **Chemical loss by type**: **Loss in transit** is the most significant contributor to chemical loss, followed by **break-ins** and **packaging discrepancies**. Other loss types, such as **employee theft** and **customer theft**, contribute significantly less to the total quantity of chemicals lost.


These insights suggest the need for targeted interventions in high-risk regions and business activities.# Data-Project
## Licensing

The files available directly from the [Data Liberation Project](https://www.data-liberation-project.org/datasets/dea-theft-and-loss-counts/) are considered public domain as they are government records. Other data files in this repository were created by **Thien Huong Tran** for the **MSBA-622-01 Data Science for Business (Spring 2025)** course at **Gonzaga University Graduate School of Business** and are shared under the Apache License [APACHE LICENSE 2.0](https://www.apache.org/licenses/LICENSE-2.0). This license applies to the files contained in this repository, including the ones available on [GitHub](https://github.com/ttran1216/Data-Project).

## Acknowledgments

This analysis was inspired by **Professor Timothy Olsen** from the **MSBA622-Data Science for Business** course and **Gonzaga University's Graduate School of Business Administration**. The initial groundwork for this project was made possible by the **Data Liberation Project**, whose efforts in obtaining, extracting, and analyzing data to getting started. Their work is available on [GitHub](https://github.com/data-liberation-project/dea-theft-and-loss-counts).

We also extend our gratitude to the **US Drug Enforcement Administration (DEA)** for making available the data related to theft and loss incidents of controlled substances. 

