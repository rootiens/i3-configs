# Dependencies
  * `i3-wm` or `i3-gaps`
  * `dunst`
  * `i3lock`
  * `i3status`
  * `compton`
  * `feh`
  * `hsetroot`
  * `rxvt-unicode`
  * `xsel`
  * `rofi`
  * `fonts-noto` `fonts-mplus`
  * `xsettingsd`
  * `xfce4-terminal`
  * `xfce4-screenshooter`
  
# Variables
  You can edit both `~/.config/i3/config` and `~/.config/i3status/config` for changing shortcuts, variablase, network interfaces etc etc
  
# Keyboard Cheatsheet

  My keybind is pretty weird, I'm more focus on easy to memorize

  * **Super + Shift + D** Launch dmenu
  * **Super + D** Launch dmenu alternative called Rofi
  * **Super + Enter** Launch i3-sensible-terminal, URxvt in this case
  * **Super + Arrow** Change focused window, if You have two or more windows in the workspace
  * **Super + Shift + Arrow** Send focused window to another edge of the screen, if You have two or more windows in the workspace
  * **Super + H** and **Super + V** Change split direction to horizontal or vertical
  * **Super + S** Change split direction, if You already have splitted windows
  * **Super + Space** Float the window, hit it again to back to tiling mode
  * **Super + 1-6** Switch to workspace 1-6
  * **Super + Shift + 1-6** Send the focused window to workspace 1-6
  * **Control + Alt + Left/Right** Switch to previous or next workspace. Only works if You have 2 workspace opened
  * **Super + R** Resize mode. In resize mode, hit Arrow keys to do resizing. Hit Enter to back to normal mode
  * **Super + C** or Alt + F4 Close window
  * **Super + Q** Quit i3wm
  * **Super + L** Lockscreen. To unlock, type your user password then hit Enter
  * **Super + Shift + R** Fully reload the configuration file. Hit this after do some modifications in the config file
  * **Super + Shift + S** for screenshot, you can add -c for clipboard
  More keybind look on the configuration file.
