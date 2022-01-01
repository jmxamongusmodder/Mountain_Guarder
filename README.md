# Mountain_Guarder
Meadow Guarder's sister game!

***

# How to Play

### Global Public Server
Play free today at [mountainguarder.herokuapp.com](https://mountainguarder.herokuapp.com)! Just go click the link, create an account, and play Mountain Guarder free, anytime, anywhere! (as long as you have WiFi)

### Installation
##### Manual Installation
I cannot distribute node.js as I do not own any rights to it, but visiting [their website](https://nodejs.org/) you can download the latest (not LTS) and install it, **checking the box "Automatically install necessary tools"**. Wait for the installation to finish, then [download the code](https://github.com/definitely-nobody-is-here/Mountain_Guarder/archive/refs/heads/master.zip) and unzip it into any folder. Run Config.bat or Config.sh (depending on system). Then simply double-click on Start.bat or Start.sh and the server is running! (those last two sentences don't apply)
To stop the server, type "stop" into the server console.
For help, type "help" into server console. (also doesn't apply)
##### Heroku Installation
[![Deploy](https://www.Herokucdn.com/deploy/button.svg)](https://Heroku.com/deploy?template=https://github.com/definitely-nobody-is-here/Mountain_Guarder)

### Joining the Game
Once the server is started, you can find your computer's name (available in Windows>System>About as "Device name"), or simply search [what's my ip](http://google.com/search?q=whats+my+ip) or click the link. The server console will tell you what port to visit and you can type either the ip address or computer name on the client side **connected to the same network as the host** and then followed by a ":" and then the port number. Example: 111.22.33.444:2000 or hostcomputer:1100. The port will always be 4000.

### Gameplay
Visit the [wiki](https://github.com/definitely-nobody-is-here/Mountain_Guarder/wiki) for more information.

***

# Troubleshooting
#### There are errors
If you are getting errors or something seems broken (missing textures or broken UI) you can [submit a bug report](https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/new?assignees=&labels=bug&template=bug-report.md&title=BUG+-+%5BSummary+here%5D) including a screenshot of the most recent logs and any errors.
#### My Server Crashed
In the case that your server crashes, [submit a bug report](https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/new?assignees=&labels=bug&template=bug-report.md&title=BUG+-+%5BSummary+here%5D) including a screenshot of the most recent logs and any error messages on the client or server.
#### I can't Connect to the Server (ERROR_Connection_Refused)
If you can't connect to the server, verify that:
 - The server is running
 - You have entered the correct port number and hostname
 - You are connected to the same WiFi network as the server
If you have verified all four of the above, try restarting the server. If your server is running on a dedicated server (like Heroku) check that your link is correct.
#### The Server is Slow
There is nothing we can do about this. It could be your connection speed or a slow server unable to run the game at full speed. Press "backslash" ("\\") ingame and in the top-right corner it should list TPS and Ping. If your Ping is high then that is likely the source of your lag. If you TPS is low then the server is lagging. Check that there is nothing eating your computer's resources by opening Task Manager (Windows) by pressing Ctrl+Shift+Esc.

If you can't resolve your problem after trying these solutions or your problem is not on this page, go to the [Issues](https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues) page and [submit a bug report](https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/new?assignees=&labels=bug&template=bug-report.md&title=BUG+-+%5BSummary+here%5D) and fill out as much information as possible.

***

# Changelog

| Version | Changes                      |
| ------- | ---------------------------- |
| 0.0.1   | <ul><li>Added base game functionality</li></ul> |
| 0.0.2   | <ul><li>Added collisions</li></ul> |
| 0.0.3   | <ul><li>Add projectiles (no textures)</li><li>Fix Heroku deploy</li><li>Add monster code</li><li>Add issue templates</li></ul> |
| 0.0.4   | <ul><li>Add monsters (they follow you around)</li><li>Players and monsters can shoot arrows</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/2" target="_blank">Fixed getting stuck in corners of collisions (Issue #2)</a></li><li>Fixed other collision issues</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/4" target="_blank">Fixed Heroku deploy again (Issue #4)</a></li></ul> |
| 0.0.5   | <ul><li>Add world</li><li>Add chunk-based positions</li><li>Implemented full map drawing</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/4" target="_blank">Fixed Heroku deploy again (Issue #4)</a></li></ul> |
| 0.0.6   | <ul><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/4" target="_blank">Fixed Heroku deploy for the last time (Issue #4)</a></li></ul> |
| 0.0.7   | <ul><li>Added monster spawners</li><li>Expanded map</li><li>Most monsters attack now</li><li>Monsters aggro on players when hit by them or their projectiles</li><li>Added snowballs</li><li>Projectiles can have patterns now</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/5" target="_blank">Fixed client not waiting for loading (Issue #5)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/7" target="_blank">Projectiles now despawn (Issue #7)</a></li></ul> |
| 0.0.8   | <ul><li>Added diagonal projectile collisions</li><li>Filled in placeholders for some of the UI</li><li>Fixed cherrybombs</li><li>Holding the mouse button now continuously attacks</li><li>Improved snowballs</li><li>Birds and Snow Birds now attack</li></ul> |
| 0.0.9   | <ul><li>Added region name sign</li><li>Expanded map and added "The Tundra" region</li><li>Added death screen</li><li>Cherry Bombs can now trigger and explode other Cherry Bombs</li><li>Snowbirds now throw faster snowballs</li></ul> |
| 0.1.0   | <ul><li>Added menu screen</li><li>Menu screen includes: changelog, announcements, credits/contributors, ads</li><li>Changed "Snowy Tundra" region to have more stuff</li><li>Spacebar can be used to heal and costs Mana</li><li>Added player textures</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/9" target="_blank">Fixed errors in client console (Issue #9)</a></li><li>Fixed monster non-deaggro bug</li><li>Added more placeholders for draggable windows</li><li>Windows now overlap each other in order of last clicked</li><li>Add a little anticheat - respawning while alive kills you</li></ul> |
| 0.1.1   | <ul><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/13" target="_blank">Fixed xp becoming <code>null</code> from killing a monster spawned by a spawner (Issue #13)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/17" target="_blank">Patched monster shooting in noattack regions (Issue #17)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/20" target="_blank">Patched automove glitch (Issue #20)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/31" target="_blank">Patched negative health (Issue #31)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/34" target="_blank">Fixed monsters crossing through nomonster regions (Issue #34)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/35" target="_blank">Fixed projectiles spawning very far from parent entity (Issue #35)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/40" target="_blank">Fixed missing collision on sign (Issue #40)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/42" target="_blank">Fixed a typo in the changelog (Issue #42)</a></li><li>Changed region borders a bit</li></ul> |
| 0.1.2   | <ul><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/19" target="_blank">Added health bars (Issue #19)</a></li><li>Added health bars</li><li>Optimized chunk loading; client now discards chunks outside of render distance</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/46" target="_blank">Fixed player tint lag (Issue #46)</a></li><li>Retextured arrow to make it more pixel consistent</li><li>Restructured movement AI to allow players and NPC to have ability to path</li></ul> |
| 0.2.0   | <ul><li>Added changing maps and two new maps</li><li>Added "Icy River" Region</li><li>Added offset layers</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/47" target="_blank">Patched player sprite clipping (Issue #47)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/49" target="_blank">Fixed typo in projectile angle calculation (Issue #49)</a></li><li>Entities that don't move don't get processed anymore</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/50" target="_blank">Fixed cherrybomb infinite animation loop glitch (Issue #50)</a></li><li>Fixed player animations</li></ul> |
| 0.2.1   | <ul><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/28" target="_blank">Patched monsters getting stuck on collisions (Issue #28)</a></li><li>Patched player leg clipping through trees</li><li>Fixed monsters unable to move</li><li>Patched layering issue in cottages</li></ul> |
| 0.3.0   | <ul><li>Added particles</li><li>Fixed getting damaged from projectiles on other maps</li><li>Added "More Games" section</li><li>Patched monsters moving indefinitely without aggro targets</li><li>Improved monster aim variability</li><li>Improved ninja star texture</li></ul> |
| 0.3.1   | <ul><li>Monsters now circle players when close enough</li><li>Cherry bomb explosion chains are now chains</li><li>Fixed monsters moving after losing aggro</li><li>Did some performange profiling</li><li>Fixed monster aggro</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/56" target="_blank">Patched projectiles spawning in collisions (Issue #56)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/52" target="_blank">Patched rubberbanding while changing maps (Issue #52)</a></li><li>Fixed monsters spawning with max HP of 100</li><li>Modified Cherry Bomb hitbox</li><li>Removed triple equal signs</li></ul> |
| 0.3.2   | <ul><li>Added debug info sent from server</li><li>Adjusted monster aggro ranges</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/60" target="_blank">Fixed player animation getting stuck (Issue #60)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/52" target="_blank">Patched rubberbanding while changing maps (Issue #52)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/66" target="_blank">Fixed missing date (Issue #66)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/61" target="_blank">Fixed missing credits (Issue #61)</a></li><li>Added chat messages for joining and leaving game</li></ul> |
| 0.4.0   | <ul><li>Implemented account system</li><li>Added server log warns and force quits</li></ul> |
| 0.4.1   | <ul><li>Fixed database unresponsive</li><li>Added change password function</li></ul> |
| 0.4.2   | <ul><li>Added settings - render distance, render quality, debug, particles - with fancy toggles!</li><li>Players now have nametags ingame</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/55" target="_blank">Projectiles can go over water (Issue #55)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/72" target="_blank">Signing in twice is now impossible (Issue #72)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/74" target="_blank">Patched players on menu screen visible ingame (Issue #74)</a></li><li>Added monster path debug and tweaked monster circle code</li></ul> |
| 0.4.3   | <ul><li>Added chat</li><li>Added disconnected button</li></ul> |
| 0.5.0   | <ul><li>Added and implemented inventory</li><li>Added equipping items (no effect yet)</li><li>Added a few item drops</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/75" target="_blank">Fixed settings not loading (Issue #75)</a></li><li>Added Offline Mode for testing without corrupting database</li><li>Patched some discrepancies</li><li>Added some s commands</li></ul> |
| 0.5.1   | <ul><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/85" target="_blank">Added the Mountain Guarder Item Creator Tool!</a></li><li>Modified item stats and added more items</li><li>Player and monster stats now apply</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/83" target="_blank">Items can only be equipped in their respective slot types now (Issue #83)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/77" target="_blank">Items no longer get visually duplicated when dragging (Issue #77)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/81" target="_blank">Added the rest of item images (Issue #81)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/84" target="_blank">Patched crash exploit through socket.io (Issue #84)</a></li></ul> |
| 0.5.2   | <ul><li>Equipped items now have an effect</li><li>Item held is now visible (swords and staffs are a bit broken)</li><li>Tweaked mana regeneration (0.5s since last use before regen starts)</li><li>Added <a href="https://teamseas.org" target="_blank">#TeamSeas Announcement</a></li><li>Players now regen automatically</li></ul> |
| 0.5.3   | <ul><li>Added a loading screen</li><li>Added some more items</li><li>Pressing "E" and "I" in chat no longer trigger the inventory</li><li>Moved the chat so it isn't off-center by 1 pixel</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/86" target="_blank">Patched items not saving on server stops (Issue #86)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/89" target="_blank">Fixed inventory overfill (Issue #89)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/88" target="_blank">Fixed maps staying black after loading (Issue #88)</a></li><li>Renamed "burst" enchantment to "swiftness"</li><li>Added JavaScript disabled page</li><li>Changed all fade effects to css transitions</li><li>Added SECURITY.md</li></ul> |
| 0.5.4   | <ul><li>Added chat autoscroll</li><li>Added debug console in-game</li><li>Added TPS and Ping to debug ui</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/91" target="_blank">Players now face in the last direction they moved in while standing (Issue #91)</a></li><li>Windows will now move to stay on screen when zooming in</li><li>Remapped chat key to "t"</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/97" target="_blank">Patched held items not clearing on unequip (Issue #97)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/100" target="_blank">Patched floating tooltip (Issue #100)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/95" target="_blank">Patched HP regen while dead (Issue #95)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/98" target="_blank">Fixed weird collisions in Outpost Inn (Issue #980)</a></li></ul> |
| 0.6.0   | <ul><li>Added NPCs</li><li>Added protection against DOS/DDOS attacks</li><li>Optimized collision detection</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/115" target="_blank">Balanced weapons (Issue #115)</a></li><li>Monster idle walk exists now</li><li>Monsters will now try and leave no monster regions</li><li>Added player death messages</li><li>Increased CherryBomb explosion range</li><li>Projectiles can now have patterns</li><li>Melee damage hitboxes now follow the player and no longer float around</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/111" target="_blank">Added socket.emit() anticheat (Issue #111)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/119" target="_blank">Prevented autoclicking without autoclicker (Issue #119)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/117" target="_blank">Fixed attacking from clicking on windows (Issue #117)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/106" target="_blank">Items no longer go into the void (Issue #106)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/114" target="_blank">Removed scroll bars on game container (Issue #114)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/102" target="_blank">Added chat size setting (Issue #102)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/118" target="_blank">Patched highlighting of inventory (Issue #118)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/108" target="_blank">Patched client not receiving player id (Issue #108)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/101" target="_blank">Patched maps changing before screen fade complete (Issue #101)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/103" target="_blank">Fixed player hitbox sizing issue (Issue #103)</a></li><li>Increased mana regen speed</li><li>Chunk borders are now visible in debug</li><li>Debug no longer shows hitboxes of entities on other maps</li><li>Patched screen flashing when changing render quality</li><li>Added some trees</li><li>Updated preview image</li><li>Fixed username character limit</li><li>Replaced manhattan distance function with square distance function</li><li>Fixed other minor bugs</li></ul> |
| 0.6.1   | <ul><li>Patched debug command-induced crashes</li><li>Monsters now flee when at low hp</li><li>Melee damage hitboxes now follow your mouse</li><li>Added license.html</li><li>Added publicly available commands in chat (/msg)</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/136" target="_blank">Patched sign in spam (Issue #136)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/139" target="_blank">Patched talking in chat on menu (Issue #139)</a></li></ul> |
| 0.6.2   | <ul><li>Monsters need a line of sight to detect you, and will lose track if they cannot see you for more than 5 seconds</li><li>Fixed NPC pathfinding issues</li><li>Improved monster pathfinding (less jittery now)</li><li>Cherry bombs no longer explode instantly</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/141" target="_blank">Fixed double-sign in bug (Issue #141)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/133" target="_blank">Fixed profanity filters (Issue #133)</a></li><li>Patched more socket.emit-related bugs</li><li>Patched crashes caused by "socket.emit('error');" (Thanks @Suvanth-Erranki!)</li><li>Added NPC waypoints to debug view and changed path visualization</li></ul> |
| 0.6.3   | <ul><li>Snowballs move faster when attacking</li><li>Added the Titanium Staff</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/143" target="_blank">Added monster spawning particles (Issue #143)</a></li><li>Balanced item rarity</li><li>Nerfed cherry bomb blast radius</li><li>Monsters will no longer circle to a point where they have no line of sight to players</li><li>Particles have variable sizes now</li><li>Fixed wierd texturing on purple orbs</li><li>Fixed noclip problems with purple orbs</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/146" target="_blank">Patched monsters aggroing from any distance (Issue #146)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/144" target="_blank">Patched chat filter bypass (Issue #144)</a></li><li>Added the invisible tables and chairs to the Outpost Inn</li></ul> |
| 0.6.4   | <ul><li>Christmas update! Everone gets a special christmas staff!</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/155" target="_blank">Fixed Bob pathing into walls (Issue #155)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/129" target="_blank">Patched errors on account creation (Issue #129)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/151" target="_blank">Patched debug toggle not changing indicator text (Issue #151)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/150" target="_blank">Fixed tree clipping through bridge railings (Issue #150)</a></li><li>Patched noclip magic orbs being invisible on client</li></ul> |
| 0.7.0   | <ul><li>Items are now droppable</li><li>Implemented tooltips</li><li>Monsters drop items instead of teleporting them into your inventory</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/152" target="_blank">Fixed all items with the same id being linked (Issue #152)</a></li><li>Fixed weapon effects not being calculated</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/156" target="_blank">Made aggro raycasting finer (Issue #156)</a></li><li>Fixed permanent item dragging</li><li>Improved preloading times</li><li>Patched infinitely spinning snowballs</li><li>Fixed monster aggro on damage</li><li>Added position values to debug screen</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/111" target="_blank">Patched server crashes from double kicks (Issue #111)</a></li></ul> |
| 0.7.1   | <ul><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/166" target="_blank">Added item highlighting (Issue #166)</a></li><li>Added more information to tooltips</li><li>Monsters now have a chance to not drop anything</li><li>Items in your offhand no longer have any effects</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/175" target="_blank">Added new collision type for tree stumps, rocks, trees, etc. (Issue #175)</a></li><li>Added a live chat feed to discord</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/160" target="_blank">Added "/help" command (Issue #160)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/170" target="_blank">Made the Steel Bow obtainable (Issue #170)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/172" target="_blank">Added snow to tree stumps (Issue #172)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/162" target="_blank">Fixed death particles flashing black (Issue #162)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/163" target="_blank">Patched monsters inactive until player approaches (0, 0) (Issue #163)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/161" target="_blank">Dropping an equip will now update your stats (Issue #161)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/169" target="_blank">Picking up items with a full inventory is no longer possible (Issue #169)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/164" target="_blank">Items no longer drop into collisions (Issue #164)</a></li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/178" target="_blank">Patched mouse position not updating (Issue #178)</a></li><li>Tweaked chat broadcasts</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/177" target="_blank">Added another bush (Issue #177)</a></li></ul> |
| 0.7.2   | <ul><li>Patched Discord live chat webhook exploit</li><li>Items only highlight when you are close to them</li><li>Changed item pickup distance</li><li><a href="https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/180" target="_blank">Changed collision size for rocks (Issue #180)</a></li></ul> |

***

# License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.

Full license can be found in the LICENSE file.

***

# Credits

##### Contributors:
- [Radioactive64](https://github.com/definitely-nobody-is-here)
- [maitian352](https://github.com/maitian352)
- [Suvanth-Erranki](https://github.com/Suvanth-Erranki/)

##### Resources:
- Various articles on the internet
- [ScriptersWar](https://www.youtube.com/channel/UC8Yp-YagXZ4C5vOduEhcjRw) [tutorial series](https://www.youtube.com/playlist?list=PLcIaPHraYF7k4FbeGIDY-1mZZdjTu9QyL)
- [Meadow Guarder](https://github.com/maitian352/Meadow-Guarder-old)

***

## Want to Contribute?

To report a bug, you can submit a [submit a bug report](https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/new?assignees=&labels=bug&template=bug-report.md&title=BUG+-+%5BSummary+here%5D) by filling out the template. Please provide as much information to the template as possible. If you would like to contribute code to this game, visit the [Github](https://github.com/definitely-nobody-is-here/Mountain_Guarder) where you can send a pull request with an application request stating your reason to create a pull request in the "comments" section along with it. If you would like to submit a suggestion you can also visit the [Github](https://github.com/definitely-nobody-is-here/Mountain_Guarder) and create a [suggestion](https://github.com/definitely-nobody-is-here/Mountain_Guarder/issues/new?assignees=&labels=suggestion&template=feature_request.md&title=SUGGESTION+-+%5BSummary+here%5D). The database is NOT publicly accessible for this game. You will have to make your own if you want to host your own server. See SECURITY.md for more information.

***

Games by [Radioactive64](https://github.com/definitely-nobody-is-here/) and [Maitian](https://github.com/maitian352/):
<ul><li><a href="https://mountainguarder.herokuapp.com/" target="_blank">Mountain Guarder</a></li><li><a href="https://meadowguarder.herokuapp.com/" target="_blank">Meadow Guarder</a></li><li><a href="https://meadowguarderold.herokuapp.com/" target="_blank">Meadow Guarder Old</a></li><li><a href="https://bobguarder.herokuapp.com/" target="_blank">Bob Guarder</a></li><li><a href="https://battleboxes.herokuapp.com/" target="_blank">BattleBoxes</a></li><li><a href="https://cubieworld.herokuapp.com/" target="_blank">CubieWorld</a></li></ul>
