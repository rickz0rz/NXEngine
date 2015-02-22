# NXEngine
A fork of NXEngine, originally located at [http://nxengine.sourceforge.net/](http://nxengine.sourceforge.net/).

This fork is being setup to allow easy building on Mac OS X.  In order to build on a Mac, you'll need to do a few things:
* Install [brew](https://github.com/Homebrew/homebrew).
* Install the SDL dependencies, if you don't already have them:
 * `brew install sdl`
 * `brew install sdl_ttf`
* Build NXEngine!
 * `make`

Run the application like you normally would, via `./nx` -- follow the instructions on the NXEngine site for the initial run, and enjoy!


#### Next steps

The next steps of this project are to:
* Port the application to SDL2
* Create a nice packaging system to turn it into a standard .app file on OS X (along with all the weird stuff that goes along with it)