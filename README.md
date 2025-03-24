# Comparative Stock & Revenue Dashboard

This repository provides a complete project for extracting and visualizing historical stock price data and revenue data for Tesla and GameStop.

## Project Overview

As a data scientist working for an investment firm, this project demonstrates how to:
- Extract historical stock data using the **yfinance** library.
- Extract revenue data via web scraping (using **requests**, **BeautifulSoup**, and **pandas.read_html**).
- Create interactive dashboards comparing stock prices with revenue using **Plotly**.

## Breakdown of the Project
- **Question 1:** Use yfinance to extract Tesla stock data, reset the index, and display the first five rows.
- **Question 2:** Use web scraping to extract Tesla revenue data and display the last five rows.
- **Question 3:** Use yfinance to extract GameStop stock data, reset the index, and display the first five rows.
- **Question 4:** Use web scraping to extract GameStop revenue data and display the last five rows.
- **Question 5:** Plot a dashboard for Tesla that shows both stock price and revenue data.
- **Question 6:** Plot a dashboard for GameStop that shows both stock price and revenue data.
- **Question 7:** Share your assignment notebook (this repository).

## Requirements

- Python 3.x
- Libraries: yfinance, pandas, requests, BeautifulSoup (bs4), html5lib, lxml, matplotlib, plotly

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/Comparative-Stock-Revenue-Dashboard.git
   cd Comparative-Stock-Revenue-Dashboard
   ```
2. **Install the Required Libraries:**
   You can install all dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```
   *Alternatively, install the following packages individually:*
   ```bash
   pip install yfinance pandas requests bs4 html5lib lxml matplotlib plotly
   ```
3. **Open the Jupyter Notebook:**
   Open the provided notebook `Dashboard_Project.ipynb` using JupyterLab or Jupyter Notebook and run all cells.

4. **Capture Screenshots:**
   Follow the instructions in the notebook to take screenshots for Questions 1 to 6. Upload those screenshots along with this notebook as required by your course.

## Files in the Repository

- `Dashboard_Project.ipynb` – The complete Jupyter Notebook with code and detailed explanations.
- `README.md` – This file.
- `requirements.txt` – (Optional) A file listing the necessary Python packages.

## License

This project is released under the MIT License.
```
