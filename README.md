# dots-2.0

## An updated, revised version of my dotfiles 

Dotfiles for this [post](https://www.reddit.com/r/unixporn/comments/wosl44/bspwm_decided_to_finally_learn_how_to_use_eww/).

I started using eww as a bar so I wrote everything from scratch and took the opportunity to be more organized. Remember to make scripts in `.bscripts` and `.config/eww/mybar/scripts` executable

Note: For the wallpaper dependant colorschemes use: `.bscripts/wallset <path to wallpaper>`

## Dependency list (may not be complete):
### AUR packages
just run this for this section (assuming you use yay):
```
yay -Sy acpi alsa-utils-git blueman brave-bin bspwm colorpicker dunst eww-git flameshot hsetroot jq kitty mantablockscreen network-manager-applet pa-applet-git picom-pijulius-git playerctl polkit-gnome polybar pulseaudio python3 rofi scrot sox spicetify-cli spotify sxhkd thunar wmctrl wpgtk xclip xdotool xprintidle --needed
```

### Other 
- [brightlight](https://github.com/multiplexd/brightlight) since for some reason xbacklight doesn't work on my machine. It's only used in `.bscripts/brightness.sh` so feel free to edit that script if you wanna use xbacklight instead.
- [pop_report](https://github.com/ikz87/pop_report) used in some scripts

Please let me know if any packages are still missing

TODO: install script (probs the only thing that's left)
