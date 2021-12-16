# macOS 11.0 Control Center for linux enviroment

## ⚠ Only support XFCE distro

![Screenshot](src/controlcenter.png)

* This is a version base from <a href="https://github.com/libredeb/comice-control-center">comice control center</a> but added more feature

## 💾 Installation

* Download the release
* Extract file
* Open terminal at directory and type
* <details> <summary>./comice-control-center</summary> </details>	

## ⚠ Attention

This is a fake control center and it build from python so it cann't control the hardware like: Change brightness, sound, turn on/off wifi,....


## ❓Issues
* Basically, i make a dark mode version but the problem is if you want to change themes from Light to Dark mode, you have to do this:
	* Open 'macOS-control-center-for-linux' and go to themes folder, you will see a folder named Light and Dark (Default is dark mode)
	* Open the Light/Dark folder, you will see 2 files
	* Copy all the file in that, then go to folder named 'comicecontrolcenter'
	* Paste the files and replace them
* A bluetooth connection is required for Control Center too. If your system doesn't have bluetooth, please don't try this because it will not work

## For Arch users
When you install this tool, you cann't see wifi connection and bluetooth. To fix it, type this in terminal
			<details> <summary>sudo pacman -S blueman iw</summary> </details>	

To fix sound doesn't display, type
		<details> <summary>sudo pacman -S pulseaudio-alsa</summary> </details>	

## Follow me
* <a href="https://www.facebook.com/kleqing24k/">Facebook</a>
* <a href="https://www.twitter.com/kleqing24k">Twitter</a>
