Ludum Dare 45
=============

Theme: Start with nothing

Concept
-------

Platformer where there are no platforms.
You begin with no platforms

* You spawn on a platform in space
* You must reach a platform in space
* You can pick up a platform type to place
* You can attach platfrom types you've picked up to existing platforms on pre-determined sides
* You can jump
* You can run
* You can roll
* When placing platforms, you can zoom out and get a full view of the level
* Then you zoom in to a third person view

### Theme

* Pangolin
	- Rock's in the sky
	- Random trees

Requirements
------------

* Levels
	- Have multiple platforms
		+ Platforms have connection points for
			* Adding
			* Receiving
			* These are direction?
	- Player can pick up platforms
	- Player spawns in level
	- Player can leave level
	- Player can restart level
		+ Player falling off restarts
		+ Player falling to death restarts after death
	- 1 - 5
* Player
	- Can walk
	- Can jump
	- Camera
		+ Can zoom
		+ Can follow player
		+ Can circle level when zoomed
	- Can place platforms
		+ Only place them where allowed
		+ Once placed, they must stay placed unless the level restarts
			* Exception: while in the zoomed mode, remember which have been placed.
				Don't commit until zooming back in
	- Can roll and jump
* UI
	- Main menu
	- Select level?
	- Begin of level title
	- End of level
		+ Time?
		+ Number of placements
		+ Expected number of placements
	- Tutorial
		+ Popup regions
	- Restart level

### Sounds

* Player
	- Walking
	- Jumping
	- Grappling?
* Level
	- Pickup
	- Add platform
	- Spawn?
	- Complete?
* Music

### Models

* Player model
	- Walk
	- Jump
	- Die
	- Roll?
* Platform models
	- Up
	- Down
	- Jump
	- Direction
	- Start
	- End
	- Pickup
* Pickup models
	- Up
	- Down
	- Jump
	- Direction
	- Pickup?

Schedule
--------

### Friday

* Concept
* Player model

### Morning (Sat)

* Player
	- Movement
	- Camera
* Platform model

### Afternoon (Sat)

* Platform
	- Placement
	- Pickup
* UI?

### Morning (Sun)

* UI
* Levels

### Afternoon (Sun)

* Levels (Complete)
* Sounds
* Polish

License Stuff
-------------

Font Peleja used by permission under SIL OFL
https://fontlibrary.org/en/font/peleja