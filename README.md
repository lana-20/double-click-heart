| [Double Click Heart](https://github.com/lana-20/50Projects50Days/tree/main/DoubleHeartClick) | [Live Demo](https://lana-20.github.io/double-click-heart/) |
|----|----|


In this project, I have an image where it says, "Double click on the image to ❤️ it".
It also says, "You liked it 0 times'.
If you double-click it, you see a heart pop up.
It has a CSS grow animation, and it shows wherever you click.
It also shows how many times you clicked.

I set a double click event and insert a heart in the exact position of the click.
On the event parameter I have the event object.
I have the client X and client Y values, the event target offset left and offset top, 
so that I can tell exactly where the element comes in from the top and the left.
I calculate that in order to find the exact position of the image.

Instead of using the <dbl> doubleclick event, I am using a single click event and
create my own double click based on the time between space, between clicks.
I you click once and just wait a decent amount of time, it's not going to be a double click.
I am testing the time between clicks and creating my own double click event.
