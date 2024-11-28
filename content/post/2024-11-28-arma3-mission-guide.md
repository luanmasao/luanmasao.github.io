---
title: 'ArmA 3 Mission Making: AI and Terrain'
date: '2024-11-26'
categories:
    - ArmA 3
tags:
    - arma3
---
While making missions with ArmA 3's editor, I developed some practices and general ideas for mission making. For me, they are useful for the conceptual stage of mission making. Most of my missions were made for A3 units and are supervised by a Zeus, but using it only as an admin tool.  In my experience, thinking about the mission as a sctructured path, from objective to objective, gives a sense of strategy behind the AIs and avoids the feeling that players are only having random encounters. I do know other mission makers prefer to generate missions automatically and don't rely on editor placed units or triggers that activate units in a predictable way. I write this only out of my personal experience and my basic knowledge(Or the lack of it) of ArmA's scripting language. I do know the awesome work that many modders and mission makers do to generate dynamic missions and an intelligent high command AI. This is not in anyway, to bash on those with skills that are way superior than mine, but only to guide those who make missions in this style or to beginners in the Eden Editor. 
***
# Location Scouting

I know this may seem exaggerated at first, but A3's terrains are so large and diverse that indeed, we sometimes have to do some "scouting" to find what fits best our planning for a mission. Some points that can affect the gameplay of a mission:
* Travel distances: consider the vehicles or the lack of them. Think about how players will navigate the map and employ the vehicles for their strategic plans.
* Terrain characteristics that have a strategic importance: hills, lakes, roads, forests etc...
* Expected engagement distances between players are defined by map objects/ biome: buildings, dense forests, tree lines, rocks and even the lack of any of natural cover in arid terrains.
* Weather/Time: besides nigh time, things like the amount of fog or daylight can drastically affect a mission and are often overlooked. Terrain also affects how you adjust these parameters.

![Example1](/images/a3post4.png "Fog")

*Open space (Airfield) was limited with the use of fog.*

It seems obvious that mission makers and players recognize these features as something important, but we often overlook these advantages over a mission. Considering that ArmA's gameplay core is the movement of large formations of infantry and vehicles, we often can't predict what most of the players will do in such a large map. Other FPS games deal with a small number of AI in small maps and few players, while in A3 you can have 80 players or 100 players playing against the same amount of AI. All of this planning over a large number of players can be overwhelming if correct planning isn't done before starting to make a mission, but some of A3's Editor tools can help you:
* Create a prototype mission:
    * Place the units that you intend to use in your map. Test their equipment and vehicles, see the limitations and advantages imposed by their weapons and how you can balance them.
    * Use editor markers to mark strategic and key locations. 

![Example2](/images/a3post.png "Markers used for reference")
*Use markers as you'd like. This is a rough example.*
* While testing assets and scouting the terrain:
    * Try to have and imagine the mission while it unfolds.
    * Think of strategies for the AI like you were leading them.
        * Do wrong strategies(Unintentional or not): not every commander is perfect. Create opportunities that players can take advantage of.
        * Think about how the factions would play your mission: are they a conventional army or a much smaller force like a guerrila? 
***
# AI Movement and Positions

AI should take advantage of the terrain and specially, respect the player's intelligence. AI doesn't see the terrain as we do. Things mentioned before like hills and forests are just in their path of engaging you. Of course some elements like trees and rocks will be used by them for cover. But there is not a commander in them that see these locations as an advantage or a limitation. More often they will just ignore their position and go straight to eliminate you. These decisions make funny situations like seeing a large formation of AI moving through the open desert in the most dumb way possible. 

![Example5](/images/a3example6.png "Dumb stuff")
*Live view of a Takistani team running toward a US Rifleman Squad. This is also a rough example.*

Creating positions like bunkers and placing sandbags over natural objects like rocks can make the AI stronger and gives them a sense of intelligence. Limiting their area of movement or disabling it completely by using the disableAI modifier creates a fierce and intelligent opponent. As mentioned before, think of them as they were you playing against other players.

One of the joys of this game is overcoming adversities through movement and cooperation between squads. Try to place AI considering all players, don't focus too much in only one place. Avoid the notion that "sniping" is always an option. It's easy to kill AI, specially when their accuracy and reaction doesn't work as well as ours, but often they can surprise players with movement. In my opinion, ArmA just becomes a shooting simulator instead of the combined arms gameplay that it represents.

## CQB Limitations

Taking consideration of ArmA's main technical features, doing missions in urban enviroments is challenging. Player and gun movement aren't the most fluid in the industry, so it can generate funny situations at times. Despite that, I think its a theme often overlooked in certain missions. Conquering cities is one of the most dangerous and fiercest battles an army can face, so it can be a challenging and rewarding mission for players. Ambush alleys, houses and building complexes that serve as strongholds for the enemy, can be used to diversify the gameplay. 

Placing AI in a way that gives them an advantage takes away some of the boredom that players often face while engaging enemies. IEDs and AP mines can create the chaos of an urban enviroment. It's one of my favorite settings in making ArmA missions: it allows the mission maker to utilize a lot of editor objets to alter the terrain. Placing destroyed assets and leveling whole neighborhoods, for me, gives a sense of a real warfare happening.

![Example4](/images/a3post3.png "Actually very op, don't do this")
*Actually a very op position for AI to be, don't do this (Or do if you hate players).*

Placing AI in a way that gives them an advantage takes away some of the boredom that players often face while engaging enemies. IEDs and AP mines can create the chaos of an urban enviroment. It's one of my favorite settings in making ArmA missions: it allows the mission maker to utilize a lot of editor objets to alter the terrain. Placing destroyed assets and leveling whole neighborhoods, for me, gives a sense of a real warfare happening.

![Example3](/images/a3post5.png "Gangsta stuff")
*AI enemies were surrounded at their supply bunker after a surprise attack from friendly troops.*

***
# This is all (For now)

I don't always think about these points above with all of its details: there's a limit in the game's engine and in my own creativity in editing missions. But atleast, they often helped me getting out of a dead end while planning a mission. Sometimes I just do bad missions and sometimes players just don't like the theme that I choose for them to play. So its with my mistakes that I've been learning to make them have more fun in these years. Also, some of the problems I've talked about AI have been fixed through the use of mods, but we all know about their side effects and compatibility issues, so some units prefer to not use them.

I guess these are some of the ideas that I've been planning for a while to write about. Expect to see more posts in the future about this theme. 
 


