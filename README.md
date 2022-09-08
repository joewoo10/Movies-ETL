## Movies-ETL (Extract, Transform, Load)

In this project an automated pipeline was created to input new data from Wikipedia data, Kaggle metadata, and MovieLens rating data, for the Amazing Prime Hackathon. Then the data was and loaded into an existing PostgreSQL database.

For this analysis, the following was completed:

  * An ETL function was written to read three data files.
  * The Wikipedia data was extracted and transformed.
  * The Kaggle and Rating data was extracted and transformed.
  * The data was loaded to a PostgreSQL Movie Database.

The ETL function was used to create, collect, and clean movie data from multiple sources. Ultimately, this transformed data was merged and loaded into PostgreSQL so it could be introduced into tables that are ready to use in the Amazing Prime Hackathon.
