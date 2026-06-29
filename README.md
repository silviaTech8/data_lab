Data Cleaning Process

The Netflix Movies and TV Shows dataset originally contained over 8,000 records. To make the analysis more manageable, a sample of 500 records was extracted, specifically from rows 501 to 1000 of the original dataset.

The following data cleaning steps were performed in Microsoft Excel:

Missing Values: The dataset was checked for missing values using Excel filters. Blank cells were found in the director, cast, and country columns. Missing values in these columns were replaced with "Unknown" or "NULL" where appropriate to ensure consistency and avoid empty fields during analysis.
Duplicate Records: The dataset was checked for duplicate entries using Excel's Remove Duplicates feature. The show_id and title columns were used as the criteria for identifying duplicates. No duplicate records were found.
Text Standardization: Text values were reviewed for consistency. Missing categorical values were standardized by replacing blanks with "Unknown" or "NULL", ensuring uniformity across the dataset.
Date Formatting: The date_added column was converted to a consistent dd-mm-yyyy date format to improve readability and enable accurate date-based analysis.
Column Headers: The column names (show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description) were already in a clean and consistent format using lowercase letters and underscores, so no modifications were required.
Data Type Validation: The release_year column was verified to contain numeric values, while the date_added column was confirmed to be stored as a valid date format. All other columns were verified to have appropriate text data types.

These cleaning steps improved the dataset's accuracy, consistency, and overall quality, making it suitable for further analysis and visualization.
