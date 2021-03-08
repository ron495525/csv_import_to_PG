# csv_import_to_PG
Import CSV into pandas dataframe, clean table name + column headers and import data to PG (AWS RDS in my case) automatically

STEPS - 
import the CSV file into pandas dataframe

clean the table name and remove all symbols, spaces, capital letters

clean the column headers and remove all symbols, spaces, capital letters

convert CSV datatypes to SQL datatypes

write the create table SQL statement

import the data into the DB
