# An Intersectional Analysis of Police Arrests and Strip Searches in the Toronto Municipal, 2020-2021

## Overview of Paper and Repository

This repository and paper analyzes the gender and racial identity of 'suspects' who have undergone strip searches by the Toronto Police Service in the Toronto Municipal from 2020 to 2021. The dataset used for analysis was retrieved from Open Data Toronto, under the package 'Police Race and Identity Based Data - Arrests and Strip Searches.' 

## File Structure

The repo is structured as the following:

-   `input` contains the data sources used in analysis including raw and cleaned data and relevant literature.

-   `outputs/paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper.

-   `scripts` contains the R scripts used to simulate, download and clean data.

## How to Run

1.  Run `scripts/00-download_data.R` to download raw data
2.  Run `scripts/01-data_cleaning.R` to generate cleaned data
3.  Run `outputs/paper/covid_clinic.qmd` to generate the PDF of the paper
