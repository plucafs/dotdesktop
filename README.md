<p style="text-align: center;">Welcome (^^)/</p>

# dotdesktop
A .desktop files CLI generator

## Build and run
```
# clone the repo
$ git clone https://github.com/plucafs/dotdesktop.git

# change the working directory to dotdesktop
$ cd dotdesktop

# build
$ nim c dotdesktop.nim

# run
$ ./dotdesktop

.: Welcome in dotdesktop (^^)/ :.
Name: godot
>>> godot
Version: (1.0) 3.5.2
>>> 3.5.2
Type: (Application)
>>> Application
Exec: (godot)
>>> godot
Icon: (godot)
>>> godot
Mime:
>>>
Optional godot comment: The godot engine
>>> The godot engine
Optional external comment: TODO: add mime
>>> # TODO: add mime

# TODO: add mime
[Desktop Entry]
Version=3.5.2
Type=Application
Name=godot
Comment=The godot engine
TryExec=
Exec=/path/to/godot
Icon=godot
Encoding=UTF-8
Terminal=false
MimeType=;
Actions=
GenericName=

A godot.desktop file will be created inside /home/your_username/.local/share/applications/. Proceed? Type y or n
y
Saving godot.desktop...
The file already exists!
.: Thank you for having used dotdesktop (^^)/ :.
```
