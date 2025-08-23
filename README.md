# Hyderabad Real Estate Market Analysis

## Project Overview

This project is an end-to-end exploratory data analysis (EDA) of the real estate market in Hyderabad, India. The goal is to extract, clean, and analyze property listings to uncover key trends, pricing patterns, and insights into the local market. The entire process, from data collection to final analysis, is documented in a series of Jupyter notebooks.

## Project Workflow

The project is broken down into a clear, sequential workflow, with each notebook handling a specific part of the process:

*   **`01_Initial-Webscraping-EDA-project1.ipynb`**: This notebook contains the Python script used to scrape property data from the `housing.com` website. It gathers raw data on property names, locations, prices, sizes, and more, saving the output to a raw CSV file.

*   **`02_DataWrangling-and-Cleaning-EDA-Project1.ipynb`**: Focuses on data cleaning and preprocessing. This step involves handling missing values, correcting data types, and transforming columns (like `Price` and `Size`) into a usable format for analysis.

*   **`03_Visualizations-EDA-Project1.ipynb`**: This notebook is dedicated to data visualization. It uses libraries like Matplotlib and Seaborn to create charts and plots that help in understanding property distributions, price variations across locations, and relationships between different features.

## Tools and Libraries Used

- **Data Collection**: `requests`, `BeautifulSoup`
- **Data Manipulation and Analysis**: `pandas`, `numpy`
- **Data Visualization**: `matplotlib`, `seaborn`
- **Environment**: `Jupyter Notebook`

## How to Run This Project

1.  **Clone the Repository**
    ```
    git clone https://github.com/your-username/your-repository-name.git
    ```

2.  **Install Dependencies**
    It is recommended to have the required libraries installed.
    ```
    pip install pandas numpy requests beautifulsoup4 matplotlib seaborn
    ```

3.  **Run the Notebooks**
    Open and run the Jupyter notebooks in numerical order, starting with `01_Initial-Webscraping-EDA-project1.ipynb`.
