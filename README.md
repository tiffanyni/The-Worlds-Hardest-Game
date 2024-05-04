# A Remake of the World's Hardest Game on a Game Boy Advance Emulator! 
<img width="1038" alt="Screenshot 2024-05-04 at 17 17 09" src="https://github.com/tiffanyni/My-GBA-Game/assets/167052032/76e8a080-34f7-49a6-8ecd-c468ab4573f9">

This is a game I programmed in C that will run on a Game Boy Advance emulator.
This program is similar to how you would write device drivers or parts of an operating system, which are typically written in C. The GBA devices (screen, buttons, DMA controller, etc.) are accessed via memory-mapped I/O. Note that the GBA is a very slow computer, so to optimize the performance on a resource-limited hardware device there was a focus on using certain tricks (such as using the DMA, integer math instead of floating point, and so forth) as I program. 

The objective of the game is to control the red square (using arrow keys) and move it to the green box on the right side. 

If the red square collides with any of the blue boxes, then you respawn at the starting point again. There is a counter on the bottom right corner showing you the number of fails you have accumulated so far. At any point of the game, you can press the backspace key to return to the start menu.

That's it, enjoy!!
