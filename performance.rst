Performance Guide
=================

Hardware
--------

By now, Arma 3 is a fairly old game. As such, I would expect most of today's gaming setups to be more than equipped to handle it. However, since Arma 3 loads some of the game assets at runtime and maps are huge, the game stutters often and performance seems to rely on many things other than the graphics card. So, the most important hardware advice is to run Arma 3 from a fast hard drive, i.e., from a fast PCI-express connected SSD drive.

Parameters Launcher Setup
--------------

In the "parameters" settings turn on the following parameters:

- show static background in menu
- skip logos at startup
- enable hyper threading
- enabled large-page support
- no logs

In the "launcher options" set the "action after game starts" to" close launcher after clicking play".

In-Game Setup
-------------

Rotation Blur
^^^^^^^^^^^^^

I keep rotation blur turned off at all times.

Vsync
^^^^^

Enabling Vsync provides a more stable image which translates to a smoother game experience. But also, Vsync, by nature, also lowers the framerate and creates a small delay. The game runs smooth enough without Vsync so long as the framerate stays above 50 fps, which is not always possible. I still prefer Vsync switched off, betting that I can tweak other settings in a way that it does not impede my experience.

View Distance
^^^^^^^^^^^^^

One very important factor is view distance. When all other options are exhausted, you can squeeze the last five frames you need out of your setup here. Note that changing the view distance has a larger effect if you are starting from a high value than when you're starting from a low value. E.g., reducing the view distance from 12000 meters to 11000 meters improves the framerate much more than reducing the view distance from 3000 meters to 2000 meters. Playing in an infantry role, I usually set the view distance to 3000 meters. In this setting the object view distance is still slightly above 1 km which is decent enough in most situations.

If you are playing an aircraft, you need to set your view distance to a very high value. You can trade the terrain detail to improve performance at high view distance settings.

Other Settings
^^^^^^^^^^^^^^

Apart from view the view distance, there are some other in-game settings that make a difference for performance. These are

- terrain detail
- shadow detail
- PIP (picture-in-picture)
- HDR (high dynamic range)
- AO (ambient occlusion)
- FSAA (full-scene anti-aliasing)

I recommend setting all graphics settings to "ultra" except the above. As mentioned above I recommend trading terrain detail for view distance if necessary. For the 3000 m view distance I set the terrain detail to standard. The picture-in-picture drains a lot of performance. I keep it turned off although I miss this feature especially in urban driving on role-play servers. I cannot tell the difference between the high and low HDR setting but the setting has a high impact on performance so I recommend setting it to low. Ambient occlusion makes a huge difference in the liveliness of the 3D scene. Even on a low setting, Arma 3 looks much more natural. I still play having ambient occlusion turned off. In contrast to post-processing anti-aliasing, full-scene anti-aliasing creates a noticable performance hit. I have it turned off.

All other video settings have an impact on performance of around one to two frames per second even when maxed out.