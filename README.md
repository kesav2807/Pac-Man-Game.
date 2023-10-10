# Pac-Man-Game.
It looks like you've provided an HTML document with JavaScript that creates and moves PacMan images on the webpage. Here's a brief overview of your code:

1. **HTML Structure:**
    - You have a basic HTML structure with a head section containing meta tags and a title, and a body section with two buttons.
    - The buttons trigger the `create()` and `move()` functions when clicked.

2. **JavaScript:**
    - You have declared several arrays (`pacman`, `x_pos`, `y_pos`, `x_vel`, `y_vel`, `direction`) to store information about PacMan images.
    - The `create()` function generates a new PacMan image with random positions, velocities, and adds it to the document body.

    ```javascript
    function create() {
        // ... (code to create PacMan image)
    }
    ```

    - The `move()` function handles the movement of PacMan images.
    - It checks if a PacMan image hits the boundaries of the window and changes its direction accordingly.
    - The images are updated based on their position and direction.

    ```javascript
    function move() {
        // ... (code to move PacMan images)
    }
    ```

3. **PacMan Images:**
    - You have an array `PacMan` that contains image filenames. The images change based on the direction and a flag.

4. **Animation:**
    - The `move()` function is called recursively using `setTimeout(move, 100);`, creating a simple animation loop that updates the PacMan images every 100 milliseconds.

5. **Note:**
    - The image source files (`image1.jpg`, `image2.jpg`, etc.) should be available in the correct paths for the code to work.

Make sure you have the image files in the correct locations, and you should be able to see PacMan images moving on your webpage when you click the "Add PacMan" and "Start Game" buttons.




