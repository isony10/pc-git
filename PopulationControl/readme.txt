[img]https://i.imgur.com/h0afNS6.gif[/img]
[url=https://buymeacoffee.com/creamkakao][img]https://i.imgur.com/PMHKBUE.png[/img] [/url]



[h1]Description[/h1]
A simple mod that controls the population.

This mod helps reduce late game lag.

<Before>
[img]https://i.imgur.com/a9hacPm.gif[/img]

<After>
[img]https://i.imgur.com/nAcyc3S.gif[/img]

Creates a decision to control the population. To control the population, you need to start decision.

If the population exceeds the specified value, the characters are randomly get plague or die.

Characters to die are not completely random. Characters to die are generally unimportant characters. They are too old, far from the player, or in poor health. Characters such as lords, heirs, or lords with no heir are less likely to die. So the game doesn't change much.

If the current population is already high, it will take some time to get it under control. Please be patient. In the meantime, the game may slow down a bit.

For the sake of the player's happiness, there is no population control in place for players and their courts.

Pinned characters do not die by default. So, if you have a character you don't want to die, pin them.

You can customize this mod by editing the following files.

Steam\steamapps\workshop\content\1158310\2276469612\common\script_values\PopulationControl_basic_values.txt

Save compatible.

It does not work well in multiplayer.

[b]You can achieve achievements.[/b]



[h1]Mod Compatibility[/h1]
Compatible with AGOT mod (dragons will not be killed by population control).
Also, dragoinriders, dragonslayers, etc. will not die.



[h1]Death algorithm[/h1]
These algorithms are subject to change without notice.

Population control begins when there are more than 22,500 people, and the death cycle continues until there are less than 20,000 people, and if too few people die in one cycle, the cycle stops. When the population exceeds 22,500, it starts working again.

If the target is a player or a close family member of the player, It never dies.

If the target is a spouse, concubine, or betrothal of/with the player or of a close family member of the player, It never dies.

If the target is in the player's court, It never dies. (including player's prisoner)

If the target is a member of the player's dynasty and there are no more than a 100 members(only who age <= 50), it does not die.

The player's heir is considered the player's family.

The further the target's location is from the player, the higher the probability of dying.

The ruler's son and daughter, two each, are safe.

If the dynasty's prestige is 3 or more, up to a certain number of members are protected.

If the target is a ruler, heir to a ruler, or a spouse/concubine of a ruler or heir, It never dies.

Up to the third successor of the title will not die.

Anyone has relationship with player and player's family are not dead

Anyone subject to the player's scheme does not die.

If someone is killed by population control, those close to him are not stressed.

If someone is killed by population control, his parents are penalized for fertility.

Pureblood trait holders will not be killed by population control by default.

Pinned characters will not be killed by population control by default.

Historical characters will not be killed by population control by default.
