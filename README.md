# RollABall
Unity Ball Game (Personal Project)

## Description:
- This was a project that I made in Unity’s game engine. 
- The game has a ball that you control with the arrows on the keyboard. 
- You move the ball to collect floating squares and every time you collect a square, your score goes up. 

## Process: 
- I first set up the interface for the game and the controls for the user.
- Next, I worked on the controlling of the camera, adjusting the height and angle to get it to feel just right.
- Then, the area for the ball to roll on was designed and created. This involved controlling the physics of the ball so it would not go through the ground or walls.
- Finally, I set up the collectable items. I added some polish by having them float and spin mid air. The implementation of the score was set up and the project was finished.

## Difficulties Faced:
- I had difficulties learning all the new tools that came with the Unity engine.
  - Solution: I was able to look at videos other people had done and read through the documentation on their website to figure out what each tool did.
- I struggled designing the functionality of the above head camera. Originally, the camera was in a fixed position, but I wanted to have it follow the player as the ball rolled.
  - Solution: The main camera needed to be a child of the player. That way wherever the user moved, the camera followed at an elevated location.

##New Skills Acquired:
- I discovered the importance of the separation of functionalities in the creation of a game. It is critical to have each script doing exactly what it says to avoid any unwanted and unpredictable behavior.
- It was exciting learning how an event driven program is built and how it runs. 
- I learned about the structure of game programming.
