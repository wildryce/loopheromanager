# [Loop Hero Manager](https://wildryce.github.io/loopheromanager/)
A tool for the game Loop Hero to plan tile placements and find efficient setups.  

[![](https://github.com/wildryce/loopheromanager/blob/main/Misc/toolButton.png)](https://wildryce.github.io/loopheromanager/)
[![](https://github.com/wildryce/loopheromanager/blob/main/Misc/layoutsButton.png)](https://github.com/wildryce/loopheromanager/blob/main/LAYOUTCODES.md)
[![](https://github.com/wildryce/loopheromanager/blob/main/Misc/updatesButton.png)](https://github.com/wildryce/loopheromanager/projects/1)

##

### What It Is

This tool is designed to either be used in tangent with the game 'Loop Hero' to pre-plan a run, or for testing out layouts to find the best possible stats. Using some of the main stat-based tiles used within the game, finding the best setup for both regular and synergy-based tiles can help with aiming for a successful run.

##

### How To Use It
![](https://github.com/wildryce/loopheromanager/blob/main/Screenshots/LHM_Display1.png)

The tool allows you to select from a range of different tiles to place down on the grid. To choose which tile you would like, click one of the displayed tiles along the top of the tool. With a tile selected, you can left-click and drag to begin placing the selected tile. To remove tiles, you can either switch back to the 'None' tile and draw over the tiles you want to cleaer, or alternatively you can hold right-click and drag to clear tiles. To clear the whole board at once, you can click the [DELETE] key.

Along the right-hand side is the calculator display, which shows all stats that will be affected by the currently placed tiles, along with how many of any tile you have placed. Special tiles that only generate when a condition is reached (such as a goblin camp) will display once the minimum requirement has been met.

Numbers that are displayed on top of tiles are known as 'adjacency' counts. This number will only be displayed on tiles that have adjacency bonuses, and display how many adjacent tiles there are to the specified tile. _(Adjacency in this case is tiles that are immediately touching the specified tile. Any tiles diagonal to the specified tile are not included.)_

##

### How To Access The Menu
![](https://github.com/wildryce/loopheromanager/blob/main/Screenshots/LHM_Display3.png)

To access the menu, you can either click the grey tile in the top-right corner (Labelled as "Click here or press [ESC] to open the menu"), or press the [ESCAPE] key. A few features exist within the menu.

#### Legend
* **Toggleable Tile Display:** At the top, there is a checkbox there you can select to use images instead of colored tiles. Please note that this is currently an in-progress feature and not every tile available in the tool will have an image associated with it.
* **Toggleable Tiles List:** The tiles shown here display the current tile sprite it is using. By clicking on the tile, you can either enable or disable the tile from showing up on the selectables tiles list in the tool. Any tiles disabled that have transformation requirements (such as blooming meadows requiring meadows) or grouped tiles (such as deserts and sand dunes) will be disabled alongside the tile that it is grouped with.

#### Controls/Info
* **Codes:** The textbox in the bottom right corner of the menu can be used to either copy the code of the current layout, or paste a saved or copied layout into the tool.
  * **Generate Code:** This button will clear the textbox, and generate the code for the current layout.
  * **Import Map:** This button will read the textbox, and generate the layout from the code onto the grid.

##

### Misc. Info

_Example of Images being used instead of colored tiles._
![](https://github.com/wildryce/loopheromanager/blob/main/Screenshots/LHM_Display2.png)


##

### Credits

* Original inspiration came from discord user 'Goostz' who posted excel versions of thicket-river setups for different sized columns.
* Original base concept came from reddit user 'code_chris' who made an interactive thicket-river builder for a 5x12 grid.

##

# Thank you! 
A huge thank you to all those who have given feedback and suggestions on what should be added, any math errors and more! It's been fun creating this project on the side, and although this started out as more of a small random project to try and recreate some of the game mechanics for fun, I feel that this tool can be useful to some people, including myself. More updates are planned to try an implement more synergy features, so if there are any suggestions I would love to hear them!
