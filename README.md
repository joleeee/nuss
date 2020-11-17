# NUSS - The ultimate programming keyboard
Nordic + United States + Special\
Made with scandinavian keyboards in mind. Uses both Shift and AltGr to switch keys.\
PRs for general improvements and localizations for other countries are of course welcome :)

# Installation
```sh
# cp nuss /usr/share/X11/xkb/symbols
$ setxkbmap nuss
```

# Preview
![preview](preview.png)
As you can see it also has some mathematical symbols, too.\
NOTE: AltGr+5 gives ‰ (per mille / promille), it is shortened to ... in the image.

# TODO
* Shift+AltGr+FX → 1/2 etc
* More mathematical symbols like R and Q
* Utilize the key between Shift and Z (but for what?)
* Swap ESC and CapsLock
* Swap Alt and SUPER (very useful with WMs because many applications such as firefox uses alt to switch tabs by default, and so changing the WM key to SUPER and then swapping them on the keyboard layout layer is a lot easier)
* Utilize key between FN and Ctrl for something other than "right clicking"
