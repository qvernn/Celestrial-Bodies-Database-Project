# Celestrial-Bodies-Database-Project

This is the Celestial Bodies Database I made for the Relational Database Course on freeCodeCamp. It mainly shows various celestial bodies from galaxies, stars, planets, and moons.

First, I created a database and multiple tables within it. The tables were named 'galaxy', 'star', 'planet', and 'moon' and I made sure to have set a tablename_id as primary key for each, making use of the SERIAL datatype for this column. I then added various columns to add more information for each table using different dataypes such as INT, VARCHAR, NUMERIC, BOOLEAN, and the deprecated TEXT datatype. From there, I proceeded to add in entries for each table.

I did make mistakes in the middle and so I had to use UPDATE multiple times. I also had to learn how to DROP the NOT NULL constraint in one of my columns. Plenty of Google searches was done during the entire process of building this database.

To note here is that the star table had a column serving as foreign key referencing galaxy_id, the planet table with a column serving as foreign key referencing star_id, and the moon table with a column serving as foreign key referencing planet_id. This was done since a star had to be within a galaxy, a planet near a star, and a moon assigned to a planet.

I then added one more table with comets in it.

And voila, the finished project!

It definitely felt like a lot of work to build it from scratch, hopefully I will learn how to setup a database faster.
