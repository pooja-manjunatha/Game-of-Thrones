# Game-of-Thrones
An un-normalised Game of Thrones dataset is taken from Kaggle and is normalised. Analysis is done in mysql and the same query is written in postgres.
I have created 4 tables namely: Battles, Attacker, Defender and Location
	The tables now look like this:
•	The location table has a primary key called Location_ID
•	The Battles table has a primary key called battle_number and Location_ID acts as the foreign_key 
•	The primary key of the Attacker table is Attacker_ID and there is a foreign key called Battle_Number from the Batles table
•	The primary key of the Defender table is Defender_ID and has the foreign key called Battle_Number from the Battles table
