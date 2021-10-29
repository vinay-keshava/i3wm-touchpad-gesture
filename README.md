# i3wm-touchpad-gesture

### When switching from Gnome or KDE to using i3 tiling window manager on a laptop, 
### you might be frustrated to discover that tap-to-click on your touchpad no longer functions. 
### This is how to re-enable tap-to-click in i3 by properly using X11 configuration.


#### Here’s the command to run if you’re of the tl;dr persuasion:

## sudo mkdir -p /etc/X11/xorg.conf.d && sudo tee <<'EOF' /etc/X11/xorg.conf.d/90-touchpad.conf 1> /dev/null



## Copy the contents of touchpad.conf and paste it 

### Then log out and log back in, or reboot.
