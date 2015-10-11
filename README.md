THREE.js Explore the Possiblities 
=================================
####with Jeremy Strawn and Breanna Turcsanyi

#####BEFORE YOU START
* Clone the repo (git clone https://github.com/jkstrawn/ThreeSemJs.git)
* Open IndexStart.html in your text editor. This is where we left off in the demo.

#####EXERCISES

######IndexStart.html
1. Move the cube
  * Move the cube along the y-axis
  * Move the cube along the z-axis
  * Rotate the cube about the y-axis
  * Rotate the cube the other direction
  * Rotate and move the block along an axis
  * Change the cube to another Geometry (your choice!)
  * Advanced: Start cube off the screen and have it move onto the screen (hint: use a negative x value and y value a random   number between -200 and 200)


2. Add a second cube
 * Add a second cube (careful, make sure to move it's intial location so they aren't on top of one another!)
 * Add an array of cubes and iterate over your arrary to update the position of each cube

######Index.html
1. Change the cube to a frog
  * In order to use the js loader, you must host your page.
  
      ###### On windows: Run the mongoose.exe from the folder you cloned. Open your browser to localhost:8080
      ###### On Mac: Brew install mongoose. Cd into the project and run mongoose from the cmd line. Open your browser to localhost:8080

     This will open index.html. You should see a frog on the page.
   * Open Index.html in your text editior
   * Make the frog move along the x-axis
   * Add more frogs
   * Set the start positions of the frogs off the screen
   * Make frogs randomly generate (add a random function to the renderer)
   * Randomize their starting points off the screen (hint: use a negative x value and y value a random   number between -200 and 200)

2. Shoot the frog
  * Add jquery to the scripts
  * Add a click handler to check for clicking
    - Remove frog from array if clicked
    - Remove model from scene if clicked
  * Add a clicked method on the frog object
  
To see our final solution, open IndexGame.html (note: if you want to run this file, you must rename it to index.html for the hosting)
