**Bussard Snap**

*Notes*

 * [Bussard](https://gitlab.com/technomancy/bussard) is a game, written using [LÖVE](https://love2d.org/), a popular lua-based 2D game engine
 * A fundamental part of the game is coding inside the game, to control aspects of the game with code, rather than directional keypresses

*Building*

On an up-to-date 16.04 system, install snapcraft and run `snapcraft` in the same directory as this README

*Things which work*

* Building the snap works
* Launching the game works

*Things which don't work*

 * Enter the in-game console with CTRL+Enter, no text input is possible. Possibly [bug1580463](https://bugs.launchpad.net/ubuntu/+source/snapd/+bug/1580463)
