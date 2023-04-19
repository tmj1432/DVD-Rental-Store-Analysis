# :cd: DVD Rental Store Analysis :cd:

## Introduction

In this notebook, we will be conducting a simple analysis on the DVD Rental database with SQL queries in a Jupyter environment.

The main objective of this project is to practice and expose myself to writing SQL queries to query from an actual database.

## Problem Statement
How can the DVD rental store optimise its inventory and pricing strategies to meet customer demands, increase revenue, and improve its rental performance?

## Approach

1) Load database into PostgreSQL using dvdrental.tar file

2) Connect to database using sqlalchemy & psycopg2

3) Run SQL queries to query from database

4) Visualise outputs of the SQL queries with matplotlib & seaborn

5) Conclusion & Recommendations

## Database Schema 

![dvd-rental-schema](https://user-images.githubusercontent.com/113895589/233124457-63c43d58-b7b2-45b1-80f8-a4cab2026e92.png)


## Conclusion & Recommendations

**1) Increasing rental prices for action films**

Top 3 Genres based on rental include Sports, Animation and Action

Top 3 Genres based on revenue include Sports, Sci-Fi and Animation

Notice that Action ranks 3rd based on the rental while ranking 7th based on the revenue generated. This is where the DVD store can experiment with increasing the rental prices for action films since there is a demand for action films.

**2) General price adjustments**

Other than increasing rental prices for action films, the store can also consider increasing the rental prices for popular films due to the high demand and reduce the prices for the less popular films.

The DVD rental store can also consider having promotions for these films to increase the number of rents for less popular films.

After identifying the list of film titles that has a rental price greater than the rental price of the top 3 most rented films, the DVD rental store can lower the prices of these films in order to increase the rental count of these films.

**3) Meeting customer demands**

Based on the number of rents, the DVD rental store can consider bringing in more films from the popular genres.

Based on the top 3 rented films by genre, the DVD rental store can also consider bringing in more copies of the top 3 films of every genre.

Based on the top 10 rented films, the DVD rental store can bring in more copies of the popular films.

By meeting the customer demands, the DVD rental store would be able to optimise the company's inventory and generate more revenue.

The opposite can be inferred for the less popular films & genres.
