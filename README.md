# Student Activity Analyser
## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [GUI Overview](#gui-overview)
- [CSV File Requirements](#csv-file-requirements)
- [Example](#example)
- [Contributing](#contributing)
## Project Overview  
This application analyses student activity on an online learning platform, providing insights into user engagement, behaviour, and trends. Educators and administrators can use it to better understand and optimise online learning environments.

**Key Features**:
- Import activity data from CSV files.
- Clean data by handling missing values and duplicates.
- Generate SQL tables for persistent storage.
- Calculate statistical averages of component interactions.
- Visualise user interactions with platform components.
- Analyse correlations and patterns in student behaviour.
- User-friendly GUI for data input, analysis, and visualisation.

The project is designed for anyone interested in understanding and optimising online learning environments.

## Technologies Used
- **Python**: Data preprocessing and application logic
- **SQLite**: Database management
- **Pandas**: Data manipulation
- **Matplotlib/Seaborn**: Data visualisation
- **Tkinter**: GUI development

## Installation
### Prerequisites
Python 3.10+  
Conda
### Steps to Set Up the Conda Environment
1. **Clone the repository**:
git clone https://github.com/spencerduberry/Student-Activity-Analayser_Python.git
2. **Navigate to the project directory**:
cd Student-Activity-Analayser_Python
3. **Create the Conda environment** conda env create -f environment.yml
4. **Activate the Conda environment**:
conda activate myenv
## Usage
### Running the Application
1. Launch the Jupyter Notebook:
jupyter notebook Online Learning Analysis.ipynb
2. Use the GUI to:
- Load CSV files
- View visualisations
## GUI Overview
- **Load Data**: Upload csv file
- **Prep Data**: Clean data and convert to SQL tables for persistent storage .
- **Display Averages**: Display the mode/median/mean of user interactions per component, per month.
- **Display Trends**: Visualise how component interactions vary over time.
- **Display Correlations**: Analyse correlations between variables.*  
- **Exit**: Exit program.  
\* Displaying correlations using unique identifiers such as User ID is meaningless; this feature was included as part of an academic assignment brief.
## CSV File Requirements
- Two CSV files with a matching User_ID column are required. 
- Example files (ACTIVITY_LOG.csv and USER_LOG.csv) are provided.
## Example
1. Ensure two correctly formatted CSV files are in the same directory as Online Learning Analysis.ipynb.
2. Open the Jupyter Notebook by running: jupyter notebook Online Learning Analysis.ipynb
3. Load data using the **Load Data** button.
4. Prepare data by selecting **Prep Data** and naming your SQL table.
5. Use analysis buttons (e.g., **Display Trends**) to visualise results.
## Contributing
I welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch (git checkout -b feature-name).
3. Commit your changes (git commit -m 'Add feature-name').
4. Push to the branch (git push origin feature-name).
5. Open a Pull Request.
