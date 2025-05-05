
# Celestial Bodies Database

## Project Overview

The Celestial Bodies Database is a PostgreSQL-based relational database designed to store and manage information about various celestial bodies. This project includes details about galaxies, stars, planets, moons, and comets, with tables representing these entities and their relationships.

The database structure allows users to query and interact with data about space, including the attributes and characteristics of stars, galaxies, planets, moons, and comets in a structured and organized manner.

## Features

- **Galaxies:** Stores information about different galaxies, including name, description, type, and distance from Earth.
- **Stars:** Contains details about stars such as name, type, age, and the galaxy they belong to.
- **Planets:** Includes data on planets like their type, size, and the star they orbit.
- **Moons:** A table for moons, including attributes such as their orbital period and their parent planet.
- **Comets:** Stores information about comets, including whether they have a tail and when they were discovered.

## How It Was Made

The database was created using PostgreSQL, a powerful open-source relational database management system. The schema was designed to represent various celestial bodies, with relationships established using foreign keys between stars, planets, moons, and galaxies. The database includes multiple tables to categorize and organize celestial data effectively.

### Database Schema
- `galaxy` – Stores details about galaxies.
- `star` – Stores details about stars and their corresponding galaxy.
- `planet` – Stores information about planets, including their type and size.
- `moon` – Holds information about moons and their respective planets.
- `comet` – Stores details about comets, such as their name and discovery year.

## Tools Used

- **PostgreSQL:** Relational database system used to create and manage the database.
- **SQL:** The primary language used to define the schema and insert data into the database.
- **Git:** Version control tool to track changes and push the code to GitHub.
