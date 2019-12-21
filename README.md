Fedora_31_lxqt with installed dwm (suckless.org) + removed sddm (login/display manager)

configuration files:
.bash_profile from ~
.xinitrc  from ~
compton.conf from ~/.config/
config.h from ~/.dwm/


1).bash_profile -> log in without sddm (DM) using tty1 will start 'startx' process  
2) startx reads .xinitrc file and settings from there and starts dwm (allow to switch to lxqt by commented last line)
3) compton.conf as name suggest and config.h settings for dwm (dwm-start - from dwm-users - checking this settings file)


download: 
dwm + dwm-user
compton (gives transparent effects) 
nitrogen (setting wallpaper)

files .xinitrc and config.h created automatically by programs so adding this files alone may not work
may be needed to generate and change this files by related applications.

DWM ROCKS!
