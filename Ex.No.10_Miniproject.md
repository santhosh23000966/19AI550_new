# Ex.No: 10  Implementation of 2D/3D game 
### DATE:                                                                            
### REGISTER NUMBER : 212223240153
### AIM: 
To develop a game Basic 2D Side-Scrolling Movement System in Unity 
### Algorithm:
```
1. Algorithm for the Game
1. Initialize the Scene

Add a player object (square sprite).

Add ground objects and give them a BoxCollider2D.

Add a Rigidbody2D to the player so physics works.

Add a camera to follow the player.

2. Player Movement Algorithm

Input: Keyboard → Arrow keys / A & D / Space
Output: Player character moves left/right and jumps.

Steps

Read horizontal input (“Horizontal” axis).

Multiply input by movement speed.

Apply the result to the player’s X-velocity.

Check if the jump key (“Jump”) is pressed.

If player is on the ground (isJumping == false):

Apply upward force to jump.

3. Ground Detection Algorithm

Used to prevent double jump.

When the player touches an object tagged “Ground”:

Set isJumping = false

When the player leaves the ground:

Set isJumping = true

4. Camera Follow Algorithm

Ensures the camera always shows the player.

Steps

Read the player’s X-position every frame.

Replace the camera’s X-position with the player’s X.

Keep camera Y and Z constant.

Update this every frame to create smooth following.

Overall Flow of the Game

Start the game → Camera and player are initialized.

Player presses left/right → player moves horizontally.

Player presses jump → force is applied upwards.

Camera automatically follows the player only on X.

Player continues platform movement on ground.
```  
### Program:
```
```
### Output:

### Result:
Thus the game was developed using Unity and adopted _-----------AI technology.
