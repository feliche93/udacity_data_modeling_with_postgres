## Purpose of Database

The purpose of this database in the context of the startup, Sparkify, is to create a star schema optimized for queries on song play analysis.

## Database Schema

### Fact Table


State and justify your database schema design and ETL pipeline.
[Optional] Provide example queries and results for song play analysis.

1. songplays - records in log data associated with song plays i.e. records with page NextSong
    - songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent


### Dimension Tables

2. users - users in the app
    - user_id, first_name, last_name, gender, level
3. songs - songs in music database
    - song_id, title, artist_id, year, duration
4. artists - artists in music database
    - artist_id, name, location, latitude, longitude
5. time - timestamps of records in songplays broken down into specific units
    - start_time, hour, day, week, month, year, weekday