## August 18, 2024

StepInDev is now available as a Windows app.
You can download it from the following link:
[step-in-dev-1.0.0-win-x64.zip](https://github.com/step-in-dev/release/releases/download/1.0.0/step-in-dev-1.0.0-win-x64.zip)

Make sure that the application is located in a folder that is not write-protected.

## July 31, 2024

1. Added a course on an introduction to Python using the Robot.

    ![screenshot with example](2024-07-31/new-course.png)

    Primarily, these are the same tasks that were used for Dave, but now they can be solved using Python.
    The tasks chosen do not involve pollution and variables, with a number of new tasks added.

    ```python
    # Import the Robot module
    from robot import *

    # List of available commands

    # Commands for moving the Robot
    move_right()
    move_left()
    move_up()
    move_down()
    
    # To paint a cell
    paint()

    # To check if a cell is painted
    is_cell_painted()
    is_cell_not_painted()

    # To check for a wall in a selected direction
    is_wall_right()
    is_wall_left()
    is_wall_up()
    is_wall_down()
    
    # To check if there is no wall in a selected direction
    is_free_right()
    is_free_left()
    is_free_up()
    is_free_down()
    ```

    The English grammar in the command names is not perfect, but the names consistently use up, down, left, and right.
    For non-English speaking children, this seems more appropriate.

    The movement commands contain the prefix 'move_' to avoid confusion with Turtle commands, which have 'left' and 'right' commands that behave differently.
## June 16, 2024

1. The precise limit on the number of available commands for the turtle is now displayed in the message for a task not completed.

    ![screenshot with example](2024-06-16/command-restriction.png)
2. Added the ability to view variable values for Python during step-by-step program execution.

    ![screenshot with example](2024-06-16/debugger-added.png)
3. Improved scaling of the turtle window. Now we do not try to fit the entire turtle field on the screen by adding scroll bars to the field. Instead, we allow the page content to extend beyond the screen edges. This is convenient when needing to enlarge the display while presenting on a projector.
4. Added a step-by-step execution button for Dave.
 
    ![screenshot with example](2024-06-16/dave-debugging.png)
5. Added tasks involving the use of the "for" loop for the turtle in Python.
