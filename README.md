Requirements
============
python, python-keybinder

Usage
=====
For now, the grid layout is a "static" 5 x 5 grid. It is automatically calculated from the dimensions of your monitor.

Currently, all you have to do is run the executable and it will bind the following shortcuts:

<table>
  <tr>
    <th>Keybinding</th><th>Action</th>
  </tr>
  <tr>
    <td>Super + Left</td><td>Narrow active window and "dock" on the left side of the screen.</td>
  </tr>
  <tr>
    <td>Super + Right</td><td>Narrow active window and "dock" on the right side of the screen.</td>
  </tr>
  <tr>
    <td>Super + Up</td><td>Shorten active window and "dock" on the top of the screen.</td>
  </tr>
  <tr>
    <td>Super + Down</td><td>Shorten active window and "dock" on the bottom of the screen.</td>
  </tr>
  <tr>
    <td>Super + Ctrl + Left</td><td>Widen active window and "dock" on the left side of the screen.</td>
  </tr>
  <tr>
    <td>Super + Ctrl + Right</td><td>Widen active window and "dock" on the right side of the screen.</td>
  </tr>
  <tr>
    <td>Super + Ctrl + Up</td><td>Make taller active window and "dock" on the top of the screen.</td>
  </tr>
  <tr>
    <td>Super + Ctrl + Down</td><td>Make taller active window and "dock" on the bottom of the screen.</td>
  </tr>
</table>

Goals
=====
* Custom key-bindings via ~/.gridz file
* Configurable grid settings
  * Choose how many grid cells are used
  * Set a boundary in case you only want part of your monitor to be used for the grid
* System tray icon