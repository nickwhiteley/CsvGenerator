# CsvGenerator
Create CSVs with fake customer data. Customer names reflect common UK names. It has the columns 'ID', 'FirstName', 'LastName', 'Line1', 'Line2', 'PostTown', 'Postcode', 'Value'.

## Data
It uses the 1000 most common lastnames and the 1000 most common boy and girl baby names from a couple of years ago to generate many different name combinations.  The most common names will appear most frequently.
Postcodes follow the UK format but are not valid; the area is simply the start of the post town in most cases.  Addresses are randomised based on common street names.  
Post towns are proportionally spread based on population.
Change the script to put the output file in a suitable location (line 81) and the number of records required (line 85).