# chicago_Crimes
Predicting Crime Hotspots: Can ML Help Allocate Police Resources?

## Project Overview
This project aims to analyze historical crime data from the city of Chicago to predict future crime hotspots. By leveraging Machine Learning techniques, we explore whether predictive models can assist law enforcement in optimizing resource allocation, improving response times, and enhancing public safety.
ORIGINAL: https://www.datacamp.com/datalab/w/fa28b424-9a03-40fe-b3bd-19b847a107bb/edit
## Dataset
The dataset utilized comes from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system accessed via the Chicago Data Portal. It features reported incidents of crime, including temporal data, spatial coordinates, and crime classification strings.

## Methodology
1. **Data Preprocessing**: Handling missing locations, standardizing data types, parsing timestamps, and removing duplicate records.
2. **Exploratory Data Analysis (EDA)**: Identifying seasonal trends, generating spatial heatmaps, and analyzing crime volume by category and district.
3. **Feature Engineering**: Creating temporal features (hour, day of the week, month, seasonality) and spatial clusters.
4. **Modeling**: Training machine learning models (e.g., Random Forest, XGBoost, and Spatial-Temporal models) to forecast crime volumes by geographic bounds (police beats/districts).
5. **Evaluation**: Assessing models utilizing metrics like RMSE, F1-Score, and overall impact on resource allocation efficiency.

## Technologies Used
- **Language**: Python 3.x
- **Data Manipulation**: `pandas`, `numpy`
- **Machine Learning**: `scikit-learn`, `xgboost` 
- **Visualization**: `matplotlib`, `seaborn`, `folium` (for interactive maps), `geopandas`

## Installation & Usage
1. Clone this repository: 
   ```bash
   git clone https://github.com/samberman/chicago_Crimes.git
   ```
2. Navigate into the project directory and install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the current Chicago Crime Dataset from the Chicago Data Portal and place it in the `data/` folder.
4. Run the Jupyter notebooks provided in order to interact with the models and reproduce the analysis.
