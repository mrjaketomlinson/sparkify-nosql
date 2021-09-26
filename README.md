# Sparkify - NoSQL

Sparkify, a pretend startup, wants to analyze data on their music streaming app. What songs are being listened to in specific sessions? Which users are listening to particular songs? What songs are being listened to by specific users? This project takes CSV files full of data and transforms it into an Apache Cassandra database to create queries which answer those questions.

## Files in this project

- **event_data files** -- CSV files representing data on songs and user activity in the sparkify music streaming app.
- **cassandra_etl.ipynb** -- A jupyter notebook which does two things: (1) processes the CSV files in event_data and (2) creates Apache Cassandra tables to run queries.