# Based on Lukesmith's build and implemented configs to ubuntu !!

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/muelthebest/dwm) (window manager)
- [dwmblocks](https://github.com/muelthebest/dwmblocks) (statusbar)
- [st](https://github.com/muelthebest/st) (terminal emulator)


## Install all dependencies on ubuntu

[dependencies](https://github.com/LukeSmithxyz/LARBS/blob/master/progs.csv).

## Implementing config's build to ubuntu 

1. Install and implemented all archives on dotfiles ("Set exactly equal to repository")
2. Verify if you have xorg system implemented (default on ubuntu)
3. Make all suckless (Dwm, Dwmblocks, Dmenu, St)
4. Remove your display manager running on ubuntu is: ( sudo apt remove --purge gdm ) -- to install is - ( sudo apt install gdm ) 
5. Verify if xorg was been setup and reinstall system. 
