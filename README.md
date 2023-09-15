# BetterFOV

BetterFOV is a modification based on [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.8.9.html) for the [Minecraft](https://www.minecraft.net/) version 1.8.9.

It provides the functionality to set a new upper limit to the [Field Of View](https://en.wikipedia.org/wiki/Field_of_view) value (FOV) of the game. Minecraft only allows a value of up to 110 (Quake Pro) out of the box.

The new maximum value is 150, but can be changed. To do so, open the configuration file `%appdata%/.minecraft/config/betterfov.cfg` and edit `max-value`. It should be noted that Forge must have already been started once with this mod in order for the configuration file to be generated.

In addition, there is now the command `/fov <value>`, which allows you to adjust the FOV value as desired. Of course, this can also be combined with an AutoText feature, e. g. from [LabyMod](https://www.labymod.net/).
