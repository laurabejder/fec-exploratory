# fec-exploratory

The campaign finance data is available in bulk at:

https://www.fec.gov/data/browse-data/?tab=bulk-data

I have uploaded the FEC's bulk data (2008-2022) into a postgres database using [this open source code](https://github.com/ethan-homan/fec-gov-postgres). 

`database.ipynb` contains some example code that runs a query against the postgres database, grabs the output in a pandas dataframe and then plots that in ggplot.
