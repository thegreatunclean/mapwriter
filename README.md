mapwriter
=========

MapWriter: A minimap mod for Minecraft

Modified to more faithfully recreate the Anvil region format.  Add a dummy level.dat and you can open these region files with tools like MCEdit.  
Such a dummy level.dat is thoughtfully provided for you.  Place it in the world folder alongside the `region` folder and away you go!  You will most likely have to switch into Chunk View in MCEdit and pan around to find your map data.

You **must** use a very recent version of MCEdit, one that supports mod blocks.


Instructions for building/development:

1) Run "gradlew setupDecompWorkspace" in the mapwriter folder.

2) Run "gradlew build" in the mapwriter folder.

3) ???

4) PROFIT

Reobfuscation and Packaging:

1) Edit the version numbers in mapwriter.forge.MwForge and build.gradle.
   The version numbers in mcmod.info should automatically be set to the same
   versions as set in the build.gradle file.

2) Run "gradlew reobf".

3) The reobfuscated jar should be output to the mapwriter/build/libs folder.

Acknowledgements:

* Chrixian for the code to get death markers working.
* ProfMobius for the overlay API.
* taelnia for extrautils compatibility patch.
* LoneStar144 for minimap border and arrow textures.
* jk-5 for updating the mod to be compatible with Minecraft 1.7.

****

Licensing:  
MapWriter is without a license file, but in [this post](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286882-mapwriter-an-open-source-mini-map?comment=326) the author states it is under CC0.  
It is assumed that all previous contributors agreed to license under those terms. If this is not the case please contact me with info.  
All modifications made by myself (thegreatunclean) are licensed under CC0.  