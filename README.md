This repository contains;

    1) chinook_sql.ipynb and factbook.ipynb that uses SQL to answer questions.
    2)  The database: factbook.db and chinook.db
    3) chinook_rel.PNG: schema diagram of chinook.db

Install "ipython-sql" to allow the use of magic line function 
and other functionality for sql on jupyter notebook
    
    From Jupyter: "!pip install ipython-sql"
    using cmd: "pip install ipython-sql"

factbook_sql.ipynb contains a file that Analyzes CIA factbook by 
answering some basic questions using SQL. 
        
        The database(factbook.db) was gotten from dataquest's guided project 
        and it has a table named "facts" with the following columns;
            name - The name of the country.
            area- The country's total area (both land and water).
            area_land - The country's land area in square kilometers.
            area_water - The country's waterarea in square kilometers.
            population - The country's population.
            population_growth- The country's population growth as a percentage.
            birth_rate - The country's birth rate, or the number of births a year per 1,000 people.
            death_rate - The country's death rate, or the number of death a year per 1,000 people.

chinook_sql.ipynb contains a file that analyses chinook database. 
The Chinook database contains information about a 
fictional digital music shop - kind of like a mini-iTunes store.

    The database(chinook.db) was gotten from dataquest's guided project 
    and it has 11 tables that are closely related.The schema diagram which shows
    the tables name and their relationship can be found in "chinhook_rel.PNG"
        
