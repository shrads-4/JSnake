# so-basicly
Easy UMD navigation

A web application written in Python meant for easy navigation using Shuttle-UM Transport

This application uses data scraped from the Shuttle UM website (https://transportation.umd.edu/shuttle-um) stored in a SQL database (CockroachDB).
The front-end of the application works on the Django framework.

The user can select options from a list of departure and arrival stops and the program uses Dijkstra's algorithm to calculate and display the fastest possible route. The application uses an undirected graph to mimic the stops, with edges being weighted with the time it takes to get from one stop to another.
