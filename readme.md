This assigmnent is to create sql queries for the given databases to find certain things

SUBMISSION:


Find all the robots from The Hitchhiker's Guide to the Galaxy.
  SELECT * FROM robots WHERE source="The Hitchhiker''s Guide to the Galaxy";

Find the robot with an "anxious" personality.
  SELECT * FROM robots WHERE personality='anxious';


Find all recipes that are nut free.
  SELECT * FROM recipes WHERE nut_free='t';


Count the number of recipes that are gluten free but not vegetarian.
  SELECT COUNT(id) FROM recipes WHERE gluten_free='t' AND vegetarian='f';


Find the animal with the most legs.



Find the board game that takes the least amount of time to play.



Find the recipe that takes the most time to prepare.



Find all the robots whose name starts with the letter M.



Count the number of board games that can be played by 8 people.



Find all animals that are swimming and egg-laying.



Find all animals that are swimming and egg-laying but not flying.



Find the board game that supports the largest number of people.
