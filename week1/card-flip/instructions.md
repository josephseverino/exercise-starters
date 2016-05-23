HTML1: Card Flip
Things to Know
CSS Syntax
CSS3
Resources
A Beginner’s Guide to HTML & CSS - Shay Howe
WebPlatform: The Basics of HTML
MDN: Getting Started with CSS
CSS 2.1 Reference
MDN: Opacity
MDN: Using CSS3 Transitions
MDN: CSS3 transition property
MDN: Using CSS3 Transforms
MDN: CSS3 transform property
Objective
You have an image gallery and you want to show off your CSS skills by adding a cool effect. Create a card flip effect using CSS3 3D Transformations.

The transition should look like the following:

cardflip.jpg

Requirements
Clone the exercise-starters repo. bash $ cd ~ $ mkdir projects $ cd projects $ git clone https://github.com/RefactorU/exercise-starters

? Note: You only need to clone the exercise-starters repo once. This downloads it to your machine and instantiates it as a git repo. If you ever need to pull in updates, you can simply run git pull.

Copy the contents of ~/projects/exercise-starters/html/card-flip to a new folder: ~/projects/html1-card-flip. Use the cp -r command to recursively copy a folder.

Open ~/projects/html1-card-flip/index.html in Chrome. This is your starting point. You're now ready to add some effects! You should only modify main.css. Leave index.html and framework.css as-is.
Adjust the position of the .front and .back elements so that they are right on top of each other
Before doing anything fancy, lets see if we can get the basic effect working just with opacity. Using opacity, adjust the CSS so that only .front is visible
On hover, set the .front opacity to 0 and the .back opacity to 1.
Look up the CSS3 transition property. Set up a transition so that you have a smooth crossfade on hover.
Now we can build on this basic version to add the 3D transformation which creates the flip effect. Look up CSS3 3D Rotations and modify your code to create the card flip effect indicated in the screenshots above.
COMPLETE
