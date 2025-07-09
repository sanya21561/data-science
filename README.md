# UK Road Safety - Exploratory Data Analysis (EDA)

This project presents an Exploratory Data Analysis on UK road safety data, specifically the **accident records** from the dataset provided by the UK Department for Transport.

## Dataset

- **Source**: [UK Road Safety - Accidents and Vehicles](https://www.kaggle.com/datasets/tsiaras/uk-road-safety-accidents-and-vehicles)
- **File used**: `Accident.csv`

### Columns Analyzed
- `Accident_Index`: Unique identifier for each accident
- `1st_Road_Class`: Road class where accident occurred
- `1st_Road_Number`: Road number
- `2nd_Road_Class`: Second road class (if applicable)
- `2nd_Road_Number`: Second road number (if applicable)
- `Accident_Severity`: Level of accident severity (1 = Fatal, 2 = Serious, 3 = Slight)
- `Carriageway_Hazards`: Road hazards (e.g., Oil, Slippery, etc.)
- `Date`: Date of accident
- `Day_of_Week`: Day accident occurred
- `Did_Police_Officer_Attend_Scene_of_Accident`: Yes/No

## 🛠️ Tools and Libraries

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Jupyter Notebook

## EDA Highlights

- **Date and Time Analysis**: Trends over time, seasonal and day-wise accident distribution.
- **Severity Distribution**: Breakdown of accidents by severity levels.
- **Road Class Impact**: Analysis of accidents across different road classes.
- **Police Attendance**: Correlation between severity and whether police attended.
- **Carriageway Hazards**: Types and frequency of hazards present during accidents.

## Key Visualizations

- Bar plots of accident severity counts
- Line plot of number of accidents over time
- Heatmaps for correlation
- Count plots for categorical features

## How to Run

1. Clone this repository or download the notebook.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Download the dataset from Kaggle and place Accident.csv in the working directory.

Open the notebook:

```bash
jupyter notebook eda01.ipynb
```

## Future Work

- Merge with vehicle-level data for deeper insights.
- Geo-spatial mapping of accident locations.
- Time of day analysis if timestamp available.




