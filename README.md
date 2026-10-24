# IBM Data Science Capstone - SpaceX Falcon 9 First Stage Landing Prediction

Predicts whether the Falcon 9 first stage will land successfully, using launch data from the SpaceX API and Wikipedia.

## Contents
| File | Description |
|---|---|
| 1_jupyter-labs-spacex-data-collection-api.ipynb | Data collection with the SpaceX REST API |
| 2_jupyter-labs-webscraping.ipynb | Web scraping launch records from Wikipedia |
| 3_labs-jupyter-spacex-Data-wrangling.ipynb | Data wrangling and landing outcome label |
| 4_jupyter-labs-eda-sql.ipynb | EDA with SQL |
| 5_jupyter-labs-eda-dataviz.ipynb | EDA with visualization and feature engineering |
| 6_lab_jupyter_launch_site_location.ipynb | Interactive map with Folium |
| 7_spacex_dash_app.py | Plotly Dash dashboard |
| 8_SpaceX_Machine_Learning_Prediction.ipynb | Classification models (LR, SVM, Decision Tree, KNN) |

## Run order
Notebooks 1-3 produce `dataset_part_1.csv` and `dataset_part_2.csv`; notebook 5 produces `dataset_part_3.csv`. Each notebook also loads the course copy of its inputs from a URL, so they can be run independently.

```
pip install pandas numpy matplotlib seaborn scikit-learn folium dash plotly requests beautifulsoup4
python 7_spacex_dash_app.py
```
