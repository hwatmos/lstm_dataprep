<!-- ABOUT THE PROJECT -->
## About The Project


Python package for automating data cleaning tasks of a pandas frame for use in LSTM networks.  LSTM networks utilize longitudinal data which means that a single sample of data may contain multiple observations.  Thus, when there are multiple data features involved, a single observation has the form of a table (columns are features, rows are observations).

What this package does exactly is it takes a pandas frame that contains several dimensions as well as a time dimension and a subject id, and it helps to aggregate the data properly.  It is useful in situations when disparate data sets are used for LSTM but each set has different sampling frequency;  or when a data set must be appropriately downsampled or aggregated.  The package allows you to specify rules for handling nulls.