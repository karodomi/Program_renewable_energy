# Program_renewable_energy - Exploratory Data Analysis for photovoltaic and wind systems

##The program contains the code for cleaning process, statistics overview and Exploratory Data Analysis for photovoltaic and wind systems from real-time data from different geographical locations. The datasets are downloaded from the kaggle.com website. The data taken for the photovoltaic system are from Karnataka, India and Massachusetts, USA locations. However, the wind systems are from Yalova, Turkey and Kalundborg, Denmark. The analysis focuses on the weather parameters and how they influence the efficiency and energy generation from the renewable energy systems. Python was used as a primary language.

##The main objectives:
- to analyse the weather parameters and how they influence the system's efficiency and the power generation
- to evaluate the system's efficiency with the use of the EDA analysis
- to compare the manufactures energy output production and the real output for the wind turbines

##Datasets description:
- Photovoltaic system:
   **Karnataka, India parameters included:**
  - AC power output
  - Module temperature
  - Solar irradiation
  - Wind speed
  **Massachusetts, USA parameters included:**
  - Timestamp
  - Solar irradiation
  - Temperature
  - Humidity
  - Wind speed
  - Solar PV output

- Wind systems:
  **Yalova, Turkey parameters included:**
  - Data, time
  - Wind speed
  - Active power
  - Theoretical power curve
**Kalundborg, Denmark parameters included:**
  - Timestamp
  - Average wind speed
  - Average power generation

##Methodology:
 Analysis workflow:
 1. Data cleaning process
    - Inspection of data type and its containment
    - Managing missing values
    - Filtering unreal values
2. Exploratory Data Analysis (EDA)
    - Histograms for the density distribution
    - 2D histograms for the relationship of two values
    - Correlation heatmap to understand dependencies
    - Probability Density Functions for wind systems modelling

##Required libraries:
- NumPy
- pandas
- matplotlib
- seaborn
- scipy

##How to run the program:
1. Clone the repository.
2. Downloaded the zip file with the datasets.
3. Open the Jupiter notebook.
4. Run the code.

##Output:
- Summary of the datasets.
- EDA analysis: histograms, 2D histograms, correlation heatmap and Probability Density Functions (PDF)

##Limitations:
The datasets were downloaded from the public source and:
- can contain unreal values.
- can be incomplete.

##Future work:
Future research of this work would involve machine learning. The steps developed in this analysis, such as dataset gain, cleaning, parameter selection, and Exploratory Data Analysis, form a solid foundation for machine learning. The machine learning would begin with structured dataset retrieval, including the automated extraction of weather parameters for any chosen location. This could be achieved by linking Python code with platforms such as OpenWeather, allowing weather data to be downloaded programmatically using coordinates and timestamps, without manual collection.


