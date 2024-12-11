# Notes_and_exercises_on_Data_Structuring

Some Jupyter notebooks developed while stuiding Data Struturing and Categorical Encoding

## Contents

* **Merge:** Demonstrates how to combine DataFrames based on common columns using different merge strategies (inner, left, right, outer).
* **Concat:** Illustrates how to stack DataFrames vertically or horizontally using `pd.concat`. It covers concatenating along different axes and handling index alignment.
* **Join:** Explains how to combine DataFrames based on their indexes using `.join`. It highlights the focus on index-based merging and options for handling overlapping columns.
* **Groupby:** Demonstrates how to use the `groupby` method in Pandas to group data and calculate aggregates.
* **Pivot Tables:** Illustrates how to use pivot tables to reshape data for analysis and create summarized views.
* **Encoding:**
-   **One-Hot Encoding:** Transforms categorical features into numerical representations using `sklearn.preprocessing.OneHotEncoder`, creating binary columns for each category.
-   **Ordinal Encoding:** Assigns numerical values to categorical data based on their order using various methods, including Pandas' `cat.codes`, `pandas.factorize()`, and `sklearn.preprocessing.OrdinalEncoder`, preserving ordinal relationships.
**Data Filtering:**
- Applies different filtering techniques to select specific data subsets:
    - **Standard filtering:** Using boolean indexing with conditional statements to extract rows that meet specified criteria.
    - **Query-based filtering:** Leveraging `df.query()` for more readable and dynamic filtering, allowing for complex expressions and variable substitution.
    - **Index-based filtering:** Selecting rows based on index values using `df.loc` and `df.iloc`, providing flexibility for accessing data by labels or positions.
    - **List-based filtering:** Filtering rows based on inclusion in a list of values using `df.isin()`, enabling selection based on membership in a predefined set.
    - **Date-based filtering:** Filtering by date ranges using `df.loc`, `df.index.between()`, and other relevant methods, allowing for temporal analysis and data extraction within specific time periods.
* **Plot:** Uses box plots and heatmaps to visualize data and correlations.
* **Mutual Information:** rank features based on their importance in predicting the target variable



## Libraries Used

* Pandas
* Seaborn
* Plotly
* Matplotlib
* NumPy
* Scikit-learn
* IPython
* ipywidgets


## Datasets

- **Tips:** A built-in Seaborn dataset containing information about restaurant bills and tips, used for demonstrating encoding techniques and general data filtering operations.
- **Aircrash:** An external dataset loaded from a URL, containing information about aircraft fatalities and dates, used specifically for illustrating date-based filtering methods.
- **Titanic:**

