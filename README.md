# COVID-19 Global Data Tracker

## Project Overview
This project analyzes global COVID-19 trends through data visualization and exploratory analysis. The interactive Jupyter Notebook processes data from Our World in Data to track cases, deaths, vaccinations, and other key metrics across selected countries.

## Project Objectives
- Import and clean COVID-19 global data from reliable sources
- Analyze time trends in cases, deaths, and vaccination rates
- Compare key metrics across selected countries and regions
- Visualize trends through various charts, graphs, and maps
- Communicate meaningful insights through data storytelling

## Tools and Libraries Used
- **Python 3.x**: Core programming language
- **Jupyter Notebook**: Interactive development environment
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Plotly**: Interactive choropleth maps
- **NumPy**: Numerical computations

## Dataset
This project uses the [Our World in Data COVID-19 dataset](https://covid.ourworldindata.org/data/owid-covid-data.csv), which provides comprehensive COVID-19 statistics including:
- Daily and cumulative confirmed cases
- Daily and cumulative deaths
- Testing figures
- Vaccination data
- Various population metrics

## Features
The notebook implements the following analyses:

1. **Data Loading & Exploration**
   - Dataset overview and structure analysis
   - Initial data quality assessment
   - Missing value identification

2. **Data Cleaning & Preparation**
   - Date conversion and formatting
   - Country filtering and selection
   - Missing value handling
   - Calculation of derived metrics (death rates, vaccination rates)

3. **Time Series Analysis**
   - Total cases over time by country
   - Total deaths over time by country
   - 7-day rolling averages for new cases

4. **Comparative Analysis**
   - Bar charts comparing total cases across countries
   - Death rate comparison between selected nations
   - Vaccination progress comparisons

5. **Geographic Visualization**
   - Interactive choropleth maps showing cases per million
   - Vaccination rate distribution worldwide

6. **Insights & Findings**
   - Key observations from the data
   - Patterns and trends identified
   - Limitations and considerations

## How to Run the Project

### Prerequisites
- Python 3.6 or higher
- Jupyter Notebook or JupyterLab
- Required libraries (install using `pip install -r requirements.txt`)

### Setup Instructions
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/covid19-global-tracker.git
   cd covid19-global-tracker
   ```

2. Install required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn plotly
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Open `COVID-19_Global_Data_Tracker.ipynb` in the Jupyter interface

5. Run all cells in sequence (Cell > Run All) or run individual cells (Shift+Enter)

## Key Insights

The analysis revealed several significant patterns:

- **Case Progression**: Different regional patterns in how COVID-19 spread, with distinct waves visible across different countries
- **Mortality Rates**: Significant variation in death rates between countries, potentially reflecting differences in healthcare systems, reporting methods, population demographics, and intervention strategies
- **Vaccination Impact**: Countries with earlier and faster vaccination rollouts generally showed improved outcomes in later phases of the pandemic
- **Regional Disparities**: Clear inequities in both pandemic impact and vaccine distribution globally

## Limitations and Considerations

- Testing capacity varies significantly between countries, affecting reported case numbers
- Different countries employ varying reporting standards and methodologies
- Data gaps and reporting inconsistencies exist for some regions
- Correlation does not imply causation; multiple factors influence pandemic outcomes

## Future Enhancements
- Incorporate additional metrics like hospitalization rates and ICU occupancy
- Add policy implementation timelines to correlate with case trends
- Develop predictive modeling for future outbreak scenarios
- Create an interactive dashboard using tools like Streamlit or Dash

## Author
Presley Oluoch

## Acknowledgments
- Our World in Data for providing comprehensive COVID-19 statistics
- Johns Hopkins University Coronavirus Resource Center
- World Health Organization COVID-19 Dashboard

## License
This project is licensed under the MIT License - see the LICENSE file for details.
