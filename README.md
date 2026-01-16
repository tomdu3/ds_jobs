# Project Instructions

The Head Data Scientist at _Training Data Ltd._ has asked you to create a DataFrame called `ds_jobs_transformed` that stores the data in `customer_train.csv` much more efficiently. Specifically, they have set the following requirements:

-   Columns containing categories with only two factors must be stored as Booleans (`bool`).
-   Columns containing integers _only_ must be stored as 32-bit integers (`int32`).
-   Columns containing floats must be stored as 16-bit floats (`float16`).
-   Columns containing nominal categorical data must be stored as the `category` data type.
-   Columns containing ordinal categorical data must be stored as _ordered categories_, and not mapped to numerical values, with an order that reflects the natural order of the column.
-   The DataFrame should be filtered to only contain students with _10 or more years_ of experience at companies with _at least 1000 employees_, as their recruiter base is suited to more experienced professionals at enterprise companies.

If you call `.info()` or `.memory_usage()` methods on `ds_jobs` and `ds_jobs_transformed` after you've preprocessed it, you should notice a substantial decrease in memory usage.

## How to approach the project

1. Exploratory data analysis

2. Converting integers, floats, and unordered categories

3. Converting ordered categories

4. Filtering on ordered categorical columns

### Exploratory data analysis

Load `customer_train.csv` to begin exploring the data to understand the contents and data types of the values in each column.

#### How to find the data types and contents of a column


#### How to determine what a columns data type should be


### Converting integers, floats, and unordered categories

Convert columns containing integers to the `int32` type, floats to the `float16` type, nominal categories to the `category` type, and two-factor categories to the `bool` type.

#### Converting data types

### Converting ordered categories

Convert columns containing ordinal categorical data into ordered categories.

#### Creating ordered categorical data types


#### Creating an ordered list of work experience values


#### Converting columns into ordered categorical columns

### Filtering on ordered categorical columns

Filter the DataFrame to only contain students with _10 or more years of experience_ at companies with _at least 1000 employees_.

#### Filtering DataFrames on ordered categorical columns