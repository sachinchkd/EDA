# Real Estate Data Analysis

This project involves data wrangling, cleaning, and exploratory data analysis of real estate data from Mexico. The data is sourced from three CSV files and is combined into a single cleaned dataset for analysis.

## Notebooks

### 1. Data Wrangling and Cleaning

This notebook (`data-wrangling-with-pandas.ipynb`) covers the following steps:

1. **Import Libraries**: Import necessary libraries for data manipulation.
2. **Load Data**: Load the three CSV files into DataFrames.
3. **Inspect Data**: Check the shape, data types, and missing values of each DataFrame.
4. **Clean Data**:
    - Drop rows with missing values.
    - Standardize currency to USD.
    - Split combined latitude and longitude columns.
    - Extract state information from nested columns.
5. **Concatenate DataFrames**: Combine the cleaned DataFrames into a single DataFrame.
6. **Save Cleaned Data**: Save the cleaned DataFrame to [`data/mexico-real-estate-clean.csv`](data/mexico-real-estate-clean.csv ).

### 2. Exploratory Data Analysis

This notebook (`exploratory-data-analysis.ipynb`) covers the following steps:

1. **Import Libraries**: Import necessary libraries for data visualization.
2. **Load Cleaned Data**: Load the cleaned data from [`data/mexico-real-estate-clean.csv`](data/mexico-real-estate-clean.csv ).
3. **Inspect Data**: Check the shape and preview the first few rows of the DataFrame.
4. **Visualize Data**:
    - Create a scatter plot map using Plotly to visualize property locations and prices.

## How to Run

1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install Dependencies**:
    Ensure you have Python 3.11.8 installed. Install the required packages using pip:
    ```sh
    pip install pandas plotly matplotlib
    ```

3. **Run Notebooks**:
    Open the notebooks in Jupyter Notebook or JupyterLab and run the cells sequentially.

## Data Sources

- [`data/mexico-real-estate-1.csv`](data/mexico-real-estate-1.csv )
- [`data/mexico-real-estate-2.csv`](data/mexico-real-estate-2.csv )
- [`data/mexico-real-estate-3.csv`](data/mexico-real-estate-3.csv )

## Output

- [`data/mexico-real-estate-clean.csv`](data/mexico-real-estate-clean.csv ): The cleaned and combined dataset.

## License

This project is licensed under the MIT License.

## Acknowledgements

Special thanks to the data providers and the open-source community for their tools and libraries.

[---](https://www.kaggle.com/datasets/allankirwa/mexico-city-real-estate-dataset)

Feel free to customize this README file according to your specific needs and project details.
