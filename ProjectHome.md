# Overview #

Salmon Viewer is a 3D model viewer (currently only 3ds files).  It is written in C# and runs on Windows, Linux, and OSX.  Models are rendered in OpenGL using the [Tao Framework](http://www.taoframework.com/).  This viewer is a good tool for learning OpenGL.

# Usage #

The viewer must be used from the command line with a single argument which is the path to the 3ds file:

`SalmonViewer.exe c:\path\to\file.3ds`

_Mono users would preface that command with 'mono'_

Once loaded, you can interact with the interface with the following commands:

  * 'w','s' move forward and backward
  * 'a','d' turn left and right
  * 'z','x' move up and down
  * '-','=' move light source along x-axis
  * click and drag the mouse to change direction

As of 0.2, rotation is supported:

  * '`[`','`]`' rotate object on x axis
  * ';',''' rotate object on y-axis
  * '.','/' rotate object on z-axis


It's basically like a first-person game.

# 3ds files #

Free 3DS models are all over the internet.  The model I use below is from [here](http://www.3dnuts.com/models.shtml).

# Videos #

<a href='http://www.youtube.com/watch?feature=player_embedded&v=lX_oHFv2Mdg' target='_blank'><img src='http://img.youtube.com/vi/lX_oHFv2Mdg/0.jpg' width='425' height=344 /></a>

# Screenshots #

![http://salmon-viewer.googlecode.com/files/anubis.jpg](http://salmon-viewer.googlecode.com/files/anubis.jpg)

![http://salmon-viewer.googlecode.com/files/osx-screenshot.png](http://salmon-viewer.googlecode.com/files/osx-screenshot.png)
On OSX
