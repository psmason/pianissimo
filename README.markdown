Pianissimo is a simple audio player, which I've made for more or less for kicks. (This repository 
will also help me become familiar with github.) I don't expect this to be useful enough to become 
anyone's favorite audio player, but nevertheless it is fully functioning.  What I do hope for 
is that others might find this useful as an introductory exercise in both GUI development and using others' 
libraries.     

## Features
* Querying your music library
* Visualizing embedded album art 
* Other standard features (buttons!)

## Components
* Qt for the GUI
* Sqlite3 to store and query the music library
* Taglib to extract song data
* Bass c library for audio playback

## Documentation

Pianissimo uses doxygen, and documentation can be produced through the windows command prompt:

1. go to the directory with the source/header files
2. 'doxygen -g' 
3. edit Doxyfile in a text editor, changing EXTRACT_PRIVATE to YES
4. 'doxygen Doxyfile'
