# PA-V1
CS Coursework basic zombie game.

PA-V1 (Project Affliction) is a game I created in unity using C#. As of now the game only contains the basic aspects needed for it to be suitable for the specification but I do have some revisions planned in my own time after completion. 

The Programming Journey is listed below in mostly chronological order. Revisions are marked with //.

Plane Object Created
Player Object Created 
Player Movement & Look Scripts Created
Interaction System / Interaction Events Script Created
Weapon Model Imported / Gun Stats, Shooting, Reload, Ammo Scripts Created
Reload Animation / Recoil & //Weapon Sway Script Created
Player Health System Script Created 
Zombie Health System Script Created (Both include damage & death scripts for later use)
Zombie AI / Zombie Rotation Scripts (Funny feature)
Zombie Attack Script
//Zombie Visual Update
//Gun shoot script did not work as intended with raycasts, updated script to create projectiles.
Projectile Collision Script / Damage to Zombies Script
Death / On Kill Script (utilises previous damage & death scripts)
Enemy Spawning System / Enemy Waves Scripts
Particle Effects (Enemy hit, Enemy spawn, Enemy death, Weapon firing, Projectile trails)
//Gun Visual Update
End Game Screen
Main Menu Screen
Win Screen
Options Menu 
Audio Manager
Audio Files
Audio Scripts
FootSteps
Game Map

Future Revisions / Log.

Stats for the zombie class used to be inherited from the player class, but this created errors from inheriting my healthUI and etc. Made the scripts seperately for simplicity, however I intend to create a basic character stats script and inherit player and zombie classes from this, in order to allow for various players / enemies in future.

Interactables such as doors, health pickups, ammo pickups can be implimented as their foundations are already present, with some future modification to the ammo system to make it limited.

More weapons can be built off the weapon system and the way these weapons are used can be added and changed. Such as picking up, swapping, etc.

Story / Lore elements and a narrator.

More maps.

The issue with raycasts was unknown, projectiles were easier to use and end up fitting the game better.

Overview.

The main aim of the game is to create a basic zombie wave shooter that can be adapted with many elements. The game as it is, is playable, and sets the foundation for adding more player characters, enemy types, interactables, weapons, maps and much more.

The game has all it's basic necessary features, a player, an enemy, a weapon system, an interaction system, a health system, a weapon and a map.







