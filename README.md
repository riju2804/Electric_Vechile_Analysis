# Electric_Vechile_Analysis
🚗 Electric Vehicle Population Data Analysis

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an Electric Vehicle (EV) Population dataset using Python.

The goal is to understand EV adoption patterns, popular EV manufacturers, geographic distribution, EV types, electric driving ranges, and other important characteristics of electric vehicles.

The project uses Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, and visualization.

🎯 Objectives

The main objectives of this project are:

Analyze the growth of EV registrations over different model years.

Identify the most popular EV manufacturers.

Find cities with the highest number of EV registrations.

Analyze the distribution of different EV types.

Identify cities and counties with high EV concentrations.

Analyze the distribution of electric vehicle driving ranges.

Detect potential outliers in electric range.

Examine correlations between numerical EV features.

🛠️ Technologies Used

Python 3

Pandas – Data loading, cleaning, and analysis

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualization

Jupyter Notebook / VS Code – Development environment

📂 Dataset

The project uses an Electric Vehicle Population Data CSV dataset.

The dataset contains information such as:

Make

Model

Model Year

Electric Vehicle Type

Electric Range

City

County

And other EV-related attributes

Note: The dataset file is not included in this repository. You need to download or obtain the dataset separately and update the file path in the Python code.

🧹 Data Cleaning

The following data-cleaning operations are performed:

Checked for missing values.

Removed rows with missing values in important columns:

Make

Model Year

Electric Range

Electric Vehicle Type

City

County

Converted Model Year to numeric format.

Converted Electric Range to numeric format.

Checked for duplicate records.

Removed duplicate rows.

Checked the final data types.

📊 Exploratory Data Analysis

1. EV Registration Growth Trend

A line chart is used to analyze the number of EV registrations across different model years.

This helps identify the overall growth of electric vehicle adoption over time.

2. Top 10 EV Makes

A bar chart displays the 10 most popular EV manufacturers based on the number of registrations.

This helps identify which manufacturers have the strongest presence in the dataset.

3. Top 10 Cities by EV Count

The analysis identifies the cities with the highest number of registered electric vehicles.

This provides insight into the geographic concentration of EV adoption.

4. EV Type Distribution

The project analyzes the distribution of different electric vehicle types, such as:

Battery Electric Vehicles (BEV)

Plug-in Hybrid Electric Vehicles (PHEV)

This helps understand the composition of the EV population.

5. Top Cities and Counties

Cities are grouped with their corresponding counties to identify locations with the highest EV concentrations.

This analysis can potentially help identify areas where EV charging infrastructure may be highly needed.

📈 Additional Visualizations

Electric Range Boxplot

A boxplot is used to identify:

Median electric range

Spread of the data

Potential outliers

Electric Range Histogram

A histogram shows how electric driving ranges are distributed across the dataset.

A KDE curve is also included to visualize the overall distribution.

Correlation Heatmap

A correlation heatmap is created using numerical features to understand relationships between different numerical variables.

Values closer to:

+1 → Strong positive correlation

0 → Little or no linear correlation

-1 → Strong negative correlation

📁 Project Structure

Electric-Vehicle-Data-Analysis/
│
├── Electric_Vehicle_Population_Data.csv
├── EV_Analysis.py
├── README.md
└── images/
    ├── ev_growth_trend.png
    ├── popular_makes.png
    ├── top_cities.png
    ├── ev_type_distribution.png
    ├── top_locations.png
    ├── electric_range_boxplot.png
    ├── electric_range_distribution.png
    └── correlation_heatmap.png

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/Electric-Vehicle-Data-Analysis.git

Navigate to the project directory:

cd Electric-Vehicle-Data-Analysis

Install the required Python libraries:

pip install pandas numpy matplotlib seaborn

▶️ How to Run

Download the EV dataset.

Place the CSV file in your project directory.

Update the dataset path in the Python script.

For example:

df = pd.read_csv("Electric_Vehicle_Population_Data.csv")

Run the Python script:

python EV_Analysis.py

The program will display the analysis results and visualizations.

💡 Key Insights

The analysis can be used to understand:

The growth of electric vehicle adoption.

Which EV manufacturers are most popular.

Which cities have the highest EV concentration.

The proportion of different EV technologies.

Typical electric driving ranges.

Locations that may require additional EV charging infrastructure.

Relationships between numerical EV characteristics.

🚀 Future Improvements

Possible improvements include:

Creating an interactive dashboard using Power BI or Tableau.

Adding geographic EV distribution using maps.

Analyzing EV adoption by year and manufacturer.

Comparing BEV and PHEV performance.

Predicting future EV registration growth using machine learning.

Analyzing charging infrastructure requirements.

Adding interactive filters for cities, manufacturers, and EV types.

👨‍💻 Author

Riju Das

Python | Data Analysis | Data Visualization | Exploratory Data Analysis

⭐ Project Purpose

This project was created as a practical data-analysis project to demonstrate skills in:

Data Cleaning → Exploratory Data Analysis → Statistical Analysis → Data Visualization → Business Insights
