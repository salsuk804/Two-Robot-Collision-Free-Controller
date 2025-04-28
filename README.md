# Two-Robot-Collision-Free-Controller
Robot Controller Simulator to support two robots moving independently within the same array of size 10

Robot A starts at position 0

Robot B starts at position 1

Each robot must be able to receive and execute its own set of commands (right, left, reboot, display, show array, cancel).
You must ensure that the two robots never occupy the same cell at the same time—no collisions are allowed.

# Updated Controller Menu (Per Robot)
Each robot should have its own control menu or be selectable before issuing a command:


Select Robot: 
1. Robot A
2. Robot B
Then display:

Controller Menu:
1. Right
2. Left
3. Display
4. Reboot
5. Show Array
6. Cancel
7. Exit

# Collision Rule
If a movement command causes a robot to land on the same position as the other robot, the move should be rejected, and an appropriate error message displayed.

The robots can pass each other, but they must not stop on the same cell.

# Requirements
Both robots must maintain their own position and operation history.

Implement separate functions for handling commands for each robot.

Prevent collisions by checking positions before each move.

Use clear prompts to let the user select which robot to control.

