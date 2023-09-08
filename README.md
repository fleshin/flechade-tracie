# Tracie Progsock

Tiling window manager for linux developers

Based on bspwm window manager, using polybar with several modules, picom as composition for shadows and transparency effects.
Pywal used for UI and wallpaper color matching. Alacritty is the default terminal with all Nerd fonts available, while using bash with a custom starship prompt.

## 

## Build and install flechade tool
Install Debian 12 without any desktop environments to minimize bloat. This will get all the deps.

```
su - root -c "usermod -aG sudo $USER"; newgrp sudo;
sudo apt install golang
go install github.com/fleshin/flechade@latest
```

## Install theme set
Load customization set from the GIT repository:
```
sudo ~/go/bin/flechade -r https://github.com/fleshin/flechade-tracie
```

## Screenshots 

<p align="center"> <img src="https://raw.githubusercontent.com/fleshin/fleshin/master/tp1.png"/> </p>

<p align="center"> <img src="https://raw.githubusercontent.com/fleshin/fleshin/master/tp2.png"/> </p>

<p align="center"> <img src="https://raw.githubusercontent.com/fleshin/fleshin/master/tp3.png"/> </p>

<p align="center"> <img src="https://raw.githubusercontent.com/fleshin/fleshin/master/tp4.png"/> </p>

