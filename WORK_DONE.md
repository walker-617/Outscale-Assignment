
# SME Assignment
## Work Done (11th Apr, 2024)

#### Step 1 (Cloning the repo)

- Forked the project repo into [my account](https://github.com/walker-617).
- Cloned it into my local machine.

#### Step 2 (Installing and fixing bugs with SFML library)

- Downloaded the SFML 32-bit library and copied the `lib` and `include` folders to the `sfml` directory in the project.
- Ran the build command but encountered an error.
- Examined the code and realized there was a circular dependency issue in `PlayerController.h` and `PlayerView.h` files.
- Updated the code with forward declarations of classes.
- Included the `.dll` files in the `x64/build` folder.
- Ran the build again and encountered an error message similar to 'cannot find SFML/Graphics.h'.
- Attempted to reinstall the whole project and ran the build again, but it didn't work.
- Tried installing the SFML 64-bit library, replacing all old files and folders with the 64-bit library.
- Build was successful without any errors. Ran the application and the game loaded successfully, with all components and keystrokes working.

#### Step 3 (Adding firing bullets)

- First, added a firing sound to the left mouse click to check if the function was working, and it worked when clicked.
- Attempted to add a white circle to represent the bullet and added position and velocity.
- The game refreshed when the left mouse button was clicked.
- Utilized the internet and online tools to resolve the error, but it remained unresolved.