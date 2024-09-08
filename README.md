# bash-scripts

A collection of bash scripts and shortcuts to make your life in the terminal a bit easier.

## Installation

Copy the following commands into your terminal for an automated installation:

```bash
git clone https://github.com/pikapower9080/bash-scripts
cd bash-scripts
chmod +x install.sh
sudo ./install.sh
```

## Commands

After installing the following commands are added to `/usr/local/bin` meaning that you should be able to execute them by typing their name anywhere:

### apache2edit
Opens the apache2 config in nano and then restarts the service

### aptinstall
Updates apt, then installs a package. Example: `sudo aptinstall wget neofetch`

### killport
Looks for processes using a port and kills them with confirmation. Example: `killport 8080`

### newcmd
Interactive script to create a new bash script/command and give it execute permission. Typically requires sudo.

### shut
Shorthand of `sudo shutdown now` (shuts down your system)

### sysupdate
Runs `sudo apt update` then `sudo apt upgrade` then `sudo apt dist-upgrade` for a full system update

### temp
Shows your system temperature and updates it two times a second

### mcbackup
Creates a local backup of important minecraft server files in the ./backups directory

### diskspace
Monitors remaining disk space in real time
