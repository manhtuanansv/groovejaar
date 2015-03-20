# GrooveJaar 

This project want to provide a desktop based client for the [Grooveshark Service](http://grooveshark.com/). 

GrooveJaar is written in **JAVA**, is **OPEN SOURCE**  and support Windows, Mac and Linux systems. The aim is to have a small client that can be a good alternative to the web service of grooveshark that, in certain cases , is really slow and require a lot of resources that make the grooveshark experience really annoying.
 
 
## Build
First you have to build jgroove library
```
	git clone https://github.com/Ale46/jgroove
	cd jgroove/src
	ant -f build.xml
	cp jgroove.jar /path_of_groovejaar/libs/
	cp token.properties /path_of_groovejaar/
```
Then you can proceed to compile groovejaar with the ant build file provided with

	ant -f build.xml 

## Install

No installation is required, all you need is the compiled version and the configuration files of the programs. For this reason you can consider GrooveJaar as a portable software.


## Features

 * Search songs
 * Fetch user playlist
 * Fetch top songs
 * Fetch songs from albums
 * Retrieve useful information for every songs searched like bitrate or size..
 * Multithread
 * Cover preview and download (if present on GrooveShark)
 * Possibility to listen a song without any type of download (also with queue support)
 * Add songs to your user lib
 * Add songs to your favorite music
 * Retreive lyrics of a song
 * Notify on new available update
	

## Copyright Issue

GrooveJaar provide the possibility to download the music stream of a song. Basically this can be viewed like a "bad" thing. But on Grooveshark you can find a lot of of free music, and if this music is free you can also download without problems!
For example take a look at this album [Quorum](http://grooveshark.com/#!/album/Quorum+web+album+/4709089), is released completly free so why I can't download ?
Of course there're a lot of copyrighted songs but the software can't handle what is free and what isn't free. Also GrooveJaar don't provide nothing himself and you need to refeer to the [GrooveShark DMCA Policy] (http://www.grooveshark.com/dmca).
Anyway due to this problems the development process is definitely **stopped** and no binaries will be provided.
