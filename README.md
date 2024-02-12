# Uber
- This project studies New York for hire vehicle data 

### Data
NYC [High Volume for Hire Vehicle Records](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

### Tools
- PostgreSQL - Exploratory data analysis and cleaning.
- Docker - containerizing and hosting SQL database.
- Python (Pandas, matplotlib, seaborn) - data exploration

### Notebooks
| Notebook                                                  | Description                                      |
| --------------------------------------------------------- | ------------------------------------------------ |
| [Load Data](./notebooks/01_load_data.ipynb)               | Load data into PostgreSQL database               |
| [EDA](./notebooks/02_EDA.ipynb)                           | Initial EDA                                      |
| [Python- EDA](./notebooks/02_pythonEDA.ipynb)                           | Stronger graphical EDA using python|
| [Platform](./notebooks/02_platform.ipynb)                 | How rides differ based on platform (Uber, Lyft).              |
| [Inflows-Outflows](./notebooks/02_inflows_outflows.ipynb) | Study of inflows and outflows based on location. |
| [Time](./notebooks/02_time.ipynb) | Study how rides differ based on the time they occur.|