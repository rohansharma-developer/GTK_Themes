<h2 align="center">GTK_Themes</h2>
A list of curated themes which your Gnome Desktop look amazing!

# Dependencies
<b>The Following extensions need to be installed for the Themes to work.</b>
<li><a href="https://extensions.gnome.org/extension/19/user-themes/">https://extensions.gnome.org/extension/19/user-themes/</a></li>
<li><a href="https://extensions.gnome.org/extension/3019/user-themes-x/">https://extensions.gnome.org/extension/3019/user-themes-x/</a></li>
<br>

:warning: **The themes will not take effect without the above extension installed**
 <h4>Apt based Distros</h4>
 
``` bash
sudo apt install gnome-tweaks
```
<h4>Pacman Based Distros</h4>

``` bash
sudo pacman -S gnome-tweaks
```

# Installation
Start by creating the directories where the themes will be stored.
``` bash
cd ~/
mkdir .themes && cd .themes
```
Proceed to clone the github repo to the current directory.
``` bash
git clone https://github.com/rohansharma-developer/GTK_Themes.git
```
Copy all the contents of the folder to `.themes`
``` bash
cp -r ./GTK_Themes/* ./
```
# Usage
<p>Open `gnome-tweaks` from your app menu. Choose any theme of your choice!</p>


