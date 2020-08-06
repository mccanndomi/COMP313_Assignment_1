# COMP313_Assignment_1
Course Code: COMP313
Name: Dominic McCann
Assignment Number: 1
Name of Game: Sky Runner
Link to Video: https://drive.google.com/file/d/19c9CT-j9o1YMSrjDKI5MwYMC8ywd37gi/view?usp=sharing

## Game Description
### What is the main action of the game?
The main action of the game is to run along the generated course and collect coins. The course is generated as the player moves along it. Each time a player has moved on from a given tile a new tile is spawned and If the player jumps off the course at any point they will die.. There are 4 types of tiles. Coins, power ups and blockers can spawn on all tiles. 

1. Plain Tile, This is just a plain flat tile.
2. Ramp Tile, This is a plain tile with a ram going either up or down.
3. Gap Tile, This tile contains a gap where the player will need to jump over.
4. Corner Tile, This tile is a tile with a 90 degree corner. Where the player will need to turn correctly.

On each tile 3 different items can spawn. These items have different possibilities of spawning. With blockers being more likely followed by coins then by the magnet power up.

1. Blocker, The blocker is a large rock boulder that can either block ⅓ or ⅔ of the tile. If the player runs into the blocker the player will die and your game will be over.
2. Coins, Coins are how the player gains points. Each coin is worth one point. Once the player has run into the coin it will disappear and the players points will increase by one.
3. Magnet Power Up, If a player runs into a magnet power up they are notified by a sound. This sound lasts for 10 seconds informing the player that the power up will only last for 10 seconds. This power up lets coins fly to the player making it easier for them to collect them. You do not gain any points for getting the magnet itself.

### What is the hardest part of the game to get working in Unreal
The hardest part of the game to get working in unreal was the magnet effect of the coins. luckily I managed to find a tutorial online to help me with the transformations of the coins. Moving actors around was a challenge. Originally I had plans for a NPC to come and try to chase you down. However I really struggled with using AI to control another player. 

Another aspect that I really struggled with was the main menu. I struggled with changing using the right gamemode for the right UI. This made it hard when trying to make a pop out settings window which I ultimately decided to leave out. Because of this I was unable to get the Music toggle working as the selected gamemode did not hold the attribute I needed.

### What was the most interesting part of your game?
For me the most interesting part of my game was the procedurally generated course. My course runs on a tile basis. As the player moves past a tile a new one is spawned on the end of the course. There are 4 types of tiles, 2 of which have two subtypes, making it 6 types of tiles overall. With each tile having the possibility of spawning the course is unpredictable making it more enjoyable. The addition of the ramp tile makes it hard for the player to see what is ahead making the course more risky. 

