# Pong
A recreation of the classic video game Pong using a Python tutorial from FreeCodeCamp.com

This being my first project with Python has been really informative on some of the basics of syntax while combining my passions of programming and video games. 

![Pong](/Pong.png)

### Turtle
This tutorial used Turtle as a way to draw the game and add to the functionality. Turtle has a whole library of built in methods which allow drawing the game to be very simple and intuitive.

### .onkeypress
Another main function of the game is using the .onkeypress method to move the paddles around on the screen. This method takes 2 parameters, the function, and the key that is being pressed. Something to note, if you have a lowercase "w" but have caps lock on while playing, the key will not work. This is method is case sensitive. 

### While
To keep the game running, there is a while loop to allow the ball to keep moving on the board. The collision of the ball is defined so that it cannot go off of the top or bottom borders and if it hits the paddles, it bounces back the other way. If the ball goes beyond a paddle to the left or the right, the ball it set back to the middle of the board and the score is changed for the corresponding player. 

## OS
OS is another module that was imported into this program to allow for the collisions to play sounds. This is accomplished through the method os.system() which only takes in the sound being played. Note, "os.system('Pong.wav&')" allows for the game to keep playing while the sound plays. If you take away the ampersand, the game will pause until the sound has finished playing. 