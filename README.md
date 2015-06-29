# admin-cmd

System | Raspberry Pi | Pogoplug 
-------|--------------|-----------
  OS   | Raspbian     | Arch Linux
Install Package | sudo apt-get install *name* | pacman -Syu *name* |
Uninstall Package | sudo apt-get remove *name* | pacman -R *name* |
Package Info | apt-cache show *name*  | pacman -Qi *name* |
Package owns file | dpkg-query -S *filename* | pacman -Qo *filename* |
List files in Installed Package | dpkg -L *name* <br> dpkg -c *filename.deb* | pacman -Ql *name* |
List Installed Packages |dpkg --get-selections | pacman -Q |
Search Packages | apt-cache search *name* | pacman -Ss *name* |
Update Packages | sudo apt-get update | pacman -Syu |
Upgrade Packages| sudo apt-get upgrade | pacman -U |
