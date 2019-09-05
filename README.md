1.-The purpose of this design is to store the information of the Sparkify application so that they can obtain information about the preferences of their users for a certain song, time of duration in which the song was heard, season, schedule, etc.
2.-The star model was used, creating 4 dimensional tables and a fact table that stores the keys and common information of the tables with which it is related

Steps to excute the scripts:
1.-Configure 'create_tables.py' to put string connection and create the database
2.-Configure 'sql_queries.py' for drop and create the structure of the tables songplays,users,songs,artists,time.
3.-Execute 'create_tables.py' 
3.-Execute 'etl.ipynb' to get informations about the tables songplays,users,songs,artists,time.
4.-Execute 'etl.py' to insert data into the tables songplays,users,songs,artists,time with information of the before step (3).
5.-Execute 'test.ipynb' to test the tables(create,insert) songplays,users,songs,artists,time 


