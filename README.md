# Project: Curated NYC Restaurant Inspection Results Dataset

## Project Motivation
The New York City Department of Health and Mental Hygiene (DOHMH) publishes detailed restaurant inspection records containing every violation citation for active restaurants and college cafeterias in NYC on NYC Open Data to encourage people to engage with information produced and used by the City government. 

The goal of this project is to curate, clean, and analyze this inspection dataset using methods from the course. This project will use data curation techniques to transform raw data provided by the government agency into a clean dataset for data analysis. 

The main research questions are:

- **Borough-level comparison:** How do food safety results differ in the five boroughs? Is it related to demographic profiles such as population density?  
- **Violation patterns:** Do restaurants generally improve after multiple inspections?  
- **Cuisine-specific analysis:** Are some cuisines more likely to receive critical violations or bad grades?  
- **Seasonality:** Are there seasonal or holiday-related spikes in food safety violations?  

## How to Run

The code (final_script.ipynb) inside notebook folder is designed for **Google Colab**.

To reproduce the clean dataset: 
1. Upload and open the notebook in Google Colab
2. Mount Google Drive:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
3. Install sodapy:
    ```
    !pip install sodapy
    ```
4. Run all cells and download df_clean.csv