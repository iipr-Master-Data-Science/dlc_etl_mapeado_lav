# dlc_etl_mapeado_lav
This repo host an assignment on a ETL process (LAV mapping).

It is required to aggregate the availability of books coming from different bookstores (sources).
Implement an ETL process that takes the data from each of them and integrate them, 
with the required modifications due to the difference in the schema (see the PDF for details).  
Essentially there is a British bookstore with a simple schema, a Spanish one with a more complex one,
and an American one. The data for the latter is in the JSON file.

1. Implement an ETL process for each source that:
    - Extracts data from the source (query).
    - Performs the required transformations (including curation) of the extracted data.
    - Inserts the data in the target database.
2. Explain the decissions made.
3. Argue about the suitability of the propossed global schema, and suggest possible improvements.
