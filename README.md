
# Debian 13 Openbox tint2 xtile jgmenu configuration files

Make script install.sh executable : chmod +x ./install.sh

Just run the script instal.sh : sh ./install.sh 

This script will install necessary applications (see below) and will copy all necessary folders and files in your /home/$user/.config/ folder and will create "wallpaper" folder in your home. Just put your wallpaper images in that folder.

or

Install those applications  :

1) sudo apt install xfce4-appfinder terminator openbox jgmenu x-tile tint2 obconf   feh
 
2) Change the content of  .config/openbox/autostart file as you wish

3) Copy folders tint2 xtile jgmenu openbox etc from the "config" folder    into your /home/$USER/.config/ folder

4) Create a "wallpaper" folder in your home and put your wallpaper images in that folder.
The walllpaper will automatically change every 3 minutes. If you want to modifiy that, edit the /home/$USER/.config/openbox/wallpaperchanger2.sh


In order to display keybindings settings,  use W-k keys , or modify  the /.config/openbox/rc.xml file

Have fun, explore and change it as you wish
