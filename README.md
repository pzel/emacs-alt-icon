emacs-alt-icon
==============

###Ever feel confused when alt+tabbing between iceweasel and emacs on debian? I sure do!
<div style="margin-left: 4em">
  <img src="http://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Iceweasel_icon.svg/96px-Iceweasel_icon.svg.png" width=48 height=48>
  <img width=48 height=48 src="https://wiki.installgentoo.com/images/a/a0/Icon_Emacs.png"><small><small><sub>sneaky weasel...</sub></small></small></div>

This repo will replace the default emacs icon with the [levitating, meditating gnu](http://www.gnu.org/graphics/meditate.html). 

Now, alt+tabbing will be easier, thanks to these starkly contrasting colors:

<div style="margin-left: 4em">
  <img src="http://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Iceweasel_icon.svg/96px-Iceweasel_icon.svg.png" width=48 height=48>
  <img src="http://www.gnu.org/graphics/meditate-tiny.jpg" width=48 height=48></div>


###How to install:

If you installed Emacs from source, see method 1. If you're using your system's package, use method 2.

####Method 1: Overwrite the emacs source tree.
First, `cp -r emacs-alt-icon/etc/* $emacs_source_dir/etc`. Then, do the `./configure, make, make install` dance. The new icons should be installed.

####Method 2: Install the icons to the filesystem
`sudo cp -r emacs-alt-icon/etc/images/icons/hicolor/* /usr/share/icons/hicolor`
