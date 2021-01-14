# animMorph for DAZ Studio 
This script creates keyframe animations from an OBJ Morph Sequence in DAZ Studio. It reads the OBJ sequence, then creates one morph per frame using Morph Loader, enabling each moprh at the necessary frame. We've used this script successfully to import cloth drape animations from Marvelous Designer. Tested with DAZ Studio 4.15 and various OBJ Sequences, including those from Marvelous Designer 10 (January 2021).

I've explained the process in these articles:

- [Exporting Animations from DAZ Studio for use in Marvelous Designer](https://www.versluis.com/2015/03/how-to-export-animations-from-daz-studio-for-use-in-marvelous-designer/)
- [Importing Marvelous Designer animations into DAZ Studio](https://www.versluis.com/2015/03/how-to-export-garment-animations-from-marvelous-designer-for-use-in-daz-studio/)

There's also a video that describes the process:

[![YouTube Thumbnail](http://img.youtube.com/vi/UYqlxnpJ6JY/0.jpg)](https://www.youtube.com/watch?v=UYqlxnpJ6JY)

# What this does
animMorph helps import an OBJ sequence into DAZ Studio and turns it into an animation. An OBJ sequence is a series of standalone static 3D files that DAZ Studio does not natively support. However, we can import all OBJs in the sequence to create as many morphs as there are objects using the built-in Morph Loader tool. animMoprh then sets each morph active for a single frame, so that a seamless animation can be played back. 
While it was designed with Marvelous Designer animations in mind, the script will work for any OBJ sequence.

# Usage

- [download the latest version](https://github.com/versluis/animmorph/releases/download/1.1/animMorph-414.zip) - works in DAZ Studio 4.11, 4.12, 4.14 and 4.15
- unpack the folder and copy it into your DAZ Studio Scripts folder
- (by default that's C:\Users\Public Documents\My DAZ 3D Library\Scripts). 
- import the first OBJ in the sequence and select it
- head over to Edit - Object - Morph Loader Pro
- select all other OBJs in the sequence (except the first one you've already loaded)
- run the script for your DAZ Studio version
- take a look at the timeline and see one keyframe at every frame, changing your object in the viewport


# License
This script is released under the Creative Commons 1.0 license. 

# History
This nifty script was made by several authors:

- original concept provided by DREDMARK
- thereafter greatly overhauled by marcuswilm
- promoted by marcuswilm and myself in various online places (since 2015)

Since the original online sources for the script have been discontinued, Marcus was kind enough to host this script as [this Gist on GitHub](https://gist.github.com/marcuswilm/c2305cd494d54b9aba80bf5f43d0f7bf). We had quite a nice discussion on that thread, please check it out. Gists are not great for community coding so I've moved the project over here. 

Up until DAZ Studio 4.11, the original version of the script worked fine. Since DAZ Studio 4.12, an update was needed. ThePhilosopher reached out to the DAZ Community, where the script was tweaked (we're not sure by whom, please let me know if you do so I can give credit here). 

Currently three versions are included with this package. Note that the 4.12-4.15 versions are identical and simply duplicated for clairty.

THANK YOU for everyone who made this project possible :-)
