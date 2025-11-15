# 🚀 Space Missions Launch Analysis

An Exploratory Data Analysis of Global Rocket Launches (1957–Present)
<div align="center"> <img src="https://i.imgur.com/9hLRsjZ.jpg" height="350"/> </div>

# 📌 Overview
This project analyzes space mission launches collected from nextspaceflight.com, covering the history of space exploration beginning with the Space Race of 1957.
Through interactive visualizations and detailed exploratory techniques, the notebook uncovers:

📊 Launch frequency by country, organization, and year

🛰️ Mission success vs. failure rates

💰 Cost analysis of global launch programs

🗺️ Geographic visualization of launch behavior using choropleth maps

🔥 Competitive analysis — Cold War (USA vs USSR), top organizations over time

# 📁 Dataset Information

Source: Scraped from NextSpaceFlight

Total Records: All historical missions up to dataset scrape date

Key fields include:

Organisation, Rocket_Name, Mission, Mission_Status

Location, Date, Price, Rocket_Status

# 🧹 Data Preparation

✔️ Handling missing data

✔️ Cleaning redundant columns

✔️ Extracting Country, Year, Month

✔️ Converting outdated country names → ISO3 format

✔️ Price normalization and transformation

# Country name corrections examples:

|Raw Value	|Updated To|
|-----------|----------|
|Russia	    |Russian Federation|
|Pacific Missile Range Facility	|USA|
|Yellow Sea	|China|
|Gran Canaria	|USA|
|Kazakhstan	|Russian Federation|

# 🔍 Analysis Completed
|Analysis Task	|Techniques Used|
|---------------|---------------|
|Mission trends by organization	|Bar charts|
|Rocket status distribution	|Plotly visualizations|
|Mission success vs failure insights	|Sunburst / pie charts|
|Launch geography	|Choropleth mapping|
|Cost distribution & change over time	|Histograms & line graphs|
|Cold War competition: USA vs USSR	|Year-wise comparison|
|Launch leadership yearly	Time-series |leadership chart|

Key insights uncovered include:

**USA and Russia** dominate overall launches

Launch activity increases sharply after the year **2000**

**December** is historically the most popular launch month

Failures have significantly **reduced over time**

SpaceX emerges as recent launch leader (post-2018)

# 🛠️ Technologies Used
|Category	|Tools|
|---------|-----|
|Programming	|Python|
|Data Analysis	|Pandas, NumPy|
|Visualization	|Plotly, Seaborn, Matplotlib|
|Geospatial	|country_converter, iso3166|
|Environment	|Jupyter Notebook / Google Colab|

# ▶️ How to Run This Project

Clone the repository:

```bash
git clone https://github.com/kizons/Space_Mission_EDA.git
cd Space_Mission_EDA
jupyter notebook "Space_Missions_Analysis_(start).ipynb"
```

Load the dataset and execute:

```bash
df_data = pd.read_csv('mission_launches.csv')
```

The notebook is fully runnable end-to-end.

# 📸 Sample Visualizations

✔️ Top Space Organisations

✔️ Rocket Status Distribution

✔️ Choropleth — Launches by Country

✔️ Cold War Space Race Analysis

✔️ Failures Over Time

✔️ Sunburst: Country → Organisation → Status

(All plots are interactive within the notebook)

# 📝 Project Structure
├── mission_launches.csv        # Dataset
├── Space_Missions_EDA.ipynb    # Analysis notebook
└── README.md                   # Project documentation

# 🚀 Future Enhancements

Build a predictive model for mission success probability

Include launch site geospatial coordinates for map plotting

Add API pipeline for live updates

# 👨‍💻 Author

Kizito Ugochukwu Okafor
Data Analyst | Machine Learning Enthusiast
