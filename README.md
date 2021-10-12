<!-- Add banner here -->
![undraw_Weather_re_qsmd](https://user-images.githubusercontent.com/83410546/135469595-7be2c567-4cd0-4f46-b787-bd8f0d18f650.png)

# Climate-Data-Analysis

<!-- Add buttons here -->
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/ridhed/Weather-Dataset-Analysis?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/ridhed/Weather-Dataset-Analysis)
![GitHub issues](https://img.shields.io/github/issues-raw/ridhed/Weather-Dataset-Analysis)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ridhed/Weather-Dataset-Analysis)
![GitHub](https://img.shields.io/github/license/ridhed/Weather-Dataset-Analysis)

<!-- Described the project in brief -->
The data set loaded uses a 30-year mean between 1951 and 1980 to calculate a base temperature for that period, and then uses 5-year mean temperatures to calculate the difference between the 5-year mean and the 30-year mean for each year. The scatter plot shows the annual temperature differences.

# Table of contents

- [Project Title](#project-title)
- [How I Did The Weather Dataset Analysis](#how-i-did-the-weather-dataset-analysis)

[(Back to top)](#table-of-contents)

# How I Did The Weather Dataset Analysis

Functions Used For Analysis

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.
* isna() - function is used to detect missing values. It return a boolean same-sized object indicating if the values are NA


       
[(Back to top)](#table-of-contents)

[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)
