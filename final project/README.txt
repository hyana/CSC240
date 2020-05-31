## ---------------------------------------------------------------------------------------
##        Name: Hyana Kang
##    Filename: final project.html
##          Date: 12/12/2019
##  References: See the last part of this file
## ---------------------------------------------------------------------------------------

## Files needed
1. One main .html file: final project.html
2. Seven .jpg files : wallbump.jpg, wall.jpg, cloth.jpg, blondehair.jpg, gravelnorm.jpg, gravelbump.jpg, gravel.jpg
3. Three .js files: GLTFLoader.js, KeyboardState.js, three.min.js
4. Seven .glb files: leg.glb, leftleg.glb, rightleg.glb, heado.glb, body.glb, left.glb, right.glb
5. Seven .blend files: leftleg.blend, rightleg.blend, heado.blend, left.blend, right.blend, leg.blend, body.blend

## How to run this game
1. Extract the final project.zip file
2. Go to the folder final project
3. Find final project.html and run it with Microsoft Edge
4. The game will automatically starts!

## Goal of this game
To win this game, the player has to tag the tagger leaning on the wall.
When you start the game, you can see two characters: player and tagger.
The tagger is the character far away from the camera, and it is a non-playable character that you cannot operate.
The player is the character close to the camera, and it is a playable character that you can operate.
To move the player character, you can only use up arrow, left arrow, and right arrow of keyboard. 

-Up arrow: go towards to the front wall
-Left arrow: go towards to the left wall
-Right arrow: go towards to the right wall

You can move diagonally if you press up arrow key and left/right key at the same time.

The tagger will be staring at the wall when you start the game. 
However, after [4, 6] seconds, the tagger will turn around and gaze at you as much as it was staring at the wall.
This process will happen 10 times, and if you fail to tag the tagger before this loop ends, you will lose this game.
Also, if you try to move while the tagger is looking at you, you will lose this game,
so you have to move while the tagger is staring at the wall.
If you want to tag the tagger, you need to go to the tagger as close as you can.
Before moving, guess how long the tagger would be looking at the wall to successfully sneak up on the tagger!

If you win or lose the game, the alert message will pop up on window. 
If you press OK button on the alert message pop up, then the game will start again.


## References
collision: https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_collision_detection
gameover: https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript/Game_over