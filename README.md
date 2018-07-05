# Space run!
My game is called Space run! In “Space run!” the player controls a spaceship which is able to shoot and maneuver around. There will be obstacles as enemy spaceships which you will be able to shoot down and asteroids that will be obstacles. The enemy spaceships will also be able to shoot the player. The asteroids are not possible to shoot down.

## Game Objectives
The goal of the player is to get as far as possible and get as high score as possible before the player has either been shootdown by enemy spaceships or has runned into a enemy spaceship or asteroid. The score is awarded by surviving as long as possible and/or shooting down enemy spaceships.

## Feature List
The game will have the following features:

### Player
* The spaceship can move up, down, left, right and diagonally using the mouse/touchpad.
* The spaceship will continuously move forward and will not be able to stop or change direction.
* The spaceship will have a invisible box where it can move around.
* The spaceship can shoot a laser bolt with the left click or tapping the screen.
* After a laser bolt has been fired the player has to wait some time to be able to fire a new laser bolt.
* There will be a sound effect each time the player shoots a new laser bolt.
* The spaceship will have 3 hit points and is reduced by one each time it is hit by a enemy laser bolt, enemy spaceship or an asteroid.
* When the player is hit it will change the colour of the ship and play a sound effect indicating that the ship have been hit.
* There will be a few frames where the player is invulnerable to damage after it has been hit.
* When the player is destroyed an explosion animation and sound effect is played.
* The player will gain 10 points for every 30 frames it has moved.


### Enemy ship
* Will shoot laser bolts randomly at the player. 
* Will not be able to move up, down, left or right. Will only move forward.
* Will have 1 hit point.
* When enemy ship is hit either by the player laser bolt or player ship it will be destroyed. 
* When enemy ship is destroyed a sound effect and explosion animation is played.
* After being destroyed by the player the player will get 1000 points.
* The enemy ship will spawn randomly in a 3x3 grid. There can be multiple enemy ships in this grid.


### Asteroid
* The asteroids will spawn randomly in the same 3x3 grid as the enemy ships. There can be multiple asteroids in the same grid.
* There will be different sizes, example 1x1, 1x2 and 2x2.
* Asteroid can not be destroyed by player or enemy ships.
* When hit by laser bolt a small explosion will be animated.


### Camera
* The camera will have a fixed position. Where the invisible box that the player spaceship is in will be at the center of the camera.


### Game Controller
* There will be a “start screen” where you can choose either to start a new game, see highscores or quit the game.
* When the game has ended a new screen will appear that will give the options to either start a new game, see highscores or quit the game.
* The player  high score will be shown in the top center of the screen.
* Three dots/images will be shown on the left top corner to indicate how much health the player has left.


### Game World
* The player can move around in square that is in the middle of the screen. And cannot move outside it.
* There is no ground or sky. It will consist of a “space” environment.


## Prototype of Game View

Figure 1, Prototype

## Assets
* I will use the following assets from Unity Asset Store my game:
* https://github.com/cbdileo/warp_speed or https://assetstore.unity.com/packages/3d/environments/sci-fi/vast-outer-space-38913  for background
* https://assetstore.unity.com/packages/3d/vehicles/space/3d-voxel-cube-spaceships-sampler-65910 for space ships.
* https://assetstore.unity.com/packages/3d/environments/asteroids-pack-84988 for asteroids
* https://assetstore.unity.com/packages/audio/sound-fx/weapons/ultra-sci-fi-game-audio-weapons-pack-vol-1-113047 laser sfx
* https://assetstore.unity.com/packages/tools/particles-effects/volumetric-lines-29160 vfx for lasers
* https://assetstore.unity.com/packages/templates/packs/space-shooter-free-107260 explosion vfx
* https://assetstore.unity.com/packages/audio/sound-fx/free-casual-game-sfx-pack-54116 explosion sfx
