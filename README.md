# Airbnb Data Visualization Project

This project demonstrates basic data visualization (data viz) techniques using an open-source Airbnb data set that has been cleaned in another repo. [Click to view my Airbnb data cleansing repo.](https://github.com/mg-ds-portfolio/prj_open_airbnb_data_cleanse)

The goal is to analyze the data using data viz tools in matplotlib and seaborn, and to conduct some supplementary numerical analysis where needed.


# Overview

This project includes:
- Exploratory inspection of the dataset
- Visualization of certain aspects of the data
- High level analysis of data using visualizations and numerical tests


# Key Actions

- 
- 


# Tools Used
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook

# File Structure
``` 
notebooks/          # Jupyter notebook showing the data viz process
requirements.txt    # Python dependencies
README.md           # Project overview
data/               # Raw input (not included) and optional output files
src/                # Python scripts (reusable helper functions)
```


# How to use
1. Clone this repository:
    ```
    git clone https://github.com/mg-ds-portfolio/prj_open_airbnb_data_viz.git
    ```
2. Create and activate a virtual environment:
    ```
    python -m venv venv
    source venv/bin/activate    # On Mac/Linux
    venv\Scripts\activate       # On Windows
    ```
3. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook:
    - Navigate into the notebooks/ folder:
        ```
        cd notebooks
        ```
    - Start the Jupyter notebook server:
        ```
        jupyter notebook
        ```
        This command will launch a local web server and automatically open your default web browser showing the Jupyter interface. If the browser does not open automatically, copy the URL provided in the terminal (it will look something like `http://localhost:8888/?token=...`) and paste it into your browser.
    - In your browser, click on the relevant `.ipynb` file to open it, then run each cell in order to reproduce the data visualization results.

# Data Source

The original raw, uncleansed data comes from Kaggle: [Airbnb Listings Data](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)

The raw data was cleansed in my other repo: [Link to my Airbnb data cleansing repo](https://github.com/mg-ds-portfolio/prj_open_airbnb_data_cleanse)

(Note: Please download the dataset directly from Kaggle to comply with their usage terms.)


# License

The structure of the original dataset is shared under the Open Database License.
The contents are © the original authors and cannot be redistributed.
To use the dataset, download it directly from [Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)

