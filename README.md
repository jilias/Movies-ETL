# Movies-ETL
This repository pulls data from wiki movies and a Movies Lens dataset from kaggle.
Both lists are used to create a dataset with reviews and full details of various movies.
Everything is pushed through the ETL process.

## NOTE OF ISSUES 
After running and cleaning the dataset, Jupyter Notebook was unable to create an output to the database.
I attempted in multiple way to run the last two cells in ELT_create_database but to no avail.
The cells would run but not export the data to Postgres. It does not show an error. It just runs with the asterisk being displayed. 
I did go to the TA office hours, but neither of us could figure out how to resolve the problem
We attempted to limit the output, increase the chunksize, import other dependencies, and other modifications.
Nothing worked and the cells continued to run without an errors, but never completed.
