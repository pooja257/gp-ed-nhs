GP_dataset:
This R program downloads, processes and save the GP extended hour data from NHS website.
The code contains the url from which the original raw data was downloaded.

ED_dataset:
This R program downloads, processes and save the ED emergency visit data from NHS website.
The code contains the url from which the original raw data was downloaded.

GP_ED_merge_dataset:
This R program reads final processed file generated by GP_dataset and ED_dataset and then
merge them together with STP and Year and save it as master data.

Results:
This R program reads the master data and prepares it for machine learning by removing outliers 
and null values. It also normalizes the data for better prediction capability. It also contains
Exploratory Data Analysis done on the master data.