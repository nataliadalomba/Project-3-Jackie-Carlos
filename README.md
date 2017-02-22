# Group-4
Jacqueline Mascenik and Carlos DaLomba

# 2/22/2017
##### Based on our feedback...
- We should consider how to vary our level design so that the game is not too repetitive.
- Add sprinting
	- Test the sprintMultiplier value (How fast should sprinting be? Is it good as it is now?)
	- Polish: Could we fix the transition from sprinting back to walking?
- Fix Item Collection
	- If correct color: Hide Mesh Renderers, Spawn burst particle effect, add to points, destroy game object
- Add a score of some sort
- Add an end game condition
- How does the player know the color of the floor tells them what collectables to go towards? (Perhaps use a particle effect and sound effect at the beginning of each new color change to show the items are shiny/valuable?)
- Player visits a colorless world on death
	- How could they exit?
	- Could the player "accumulate color" power of some sort?
- Add toggleable controls screen with \






---

# 2/19/2017 - Our Current Progress...
Carlos:
As of 6:15pm 2/19/2017, we have...
- Player movement with the mouse and keyboard. (Note: Press Ctrl while playing to toggle the mouse mode between moving the cursor and rotating the player)
- Prefabs for the Player, the hazardous Red Spikes, Collectables, and the Walls.
- Player Health system, impacted by walking into red spikey objects (with animation for the player)
- The Collectable objects with rotation and color coordination with the terrain.
- Basic, temporary handling of player death (simple respawn with full health). There is no animation or wait-time for a gameover screen yet.

Some things we need that you can help with:
- We need the map/level to be laid out with more collectable objects, walls, and spikes. You can resize them if you want to vary them a little (with scaling in the Transforms). You can also edit the terrain heights to make hills for example.
- We do need some audio if you can create some for background music, and SFX when the player collects a collectable, runs into a spike, and jumps, perhaps. If you would have to grab audio from somewhere, I can create the sound effects. (Just cause licensing is complicated and I don't want to have to worry about works cited on the screen)
