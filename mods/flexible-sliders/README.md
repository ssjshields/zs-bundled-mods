# Flexible Sliders

Would you like to feel like Rambo gunning down your enemies with a gigantic health pool? Would you like to become the richest man in Zakov? Or maybe you'd like to reduce your powers to the bare minimum and try to survive when all odds are against you.

Either way, this is the mod for you. `Flexible Sliders` increases the range of possible values when customizing your gamesave in [Zero Sievert](https://store.steampowered.com/app/1782120/ZERO_Sievert/).

## Installing the mod

1. Download the [zipped mod file](./data.zip) to your machine;
1. Unzip this file. It will contain a single file named `data.win`.
1. Go to Zero Sievert's installation path
	1. If installed through Steam, go to the game properties, local files and browse.
1. Move the unzipped `data.win` file into the `ZERO Sievert` directory
	1. A message will state a file with the same name already exists. Select the option to overwrite the existing file.
1. Launch the game. Your character will now have a max amount of 10 hit points.

*Attention:* If you'd like to disable the mod eventually, you'll need to keep a backup of the original `data.win` file found in the `ZERO Sievert` directory.

## FAQ
---
**Q.** Will this mod affect my current saves?

**A.** No. The mod does not affect any current save and will only allow you to create new games with custom values.

---

**Q.** What happens if I uninstall the mod?

**A.** All the settings configured will be kept with no changes.

---

**Q.** Can this mod work with other Zero Sievert mods?

**A.** As of now, there is no way to load two mods at once. Modder cooperation would be required to merge two mods together.

---

**Q.** This mod is very tiny, why don't you make something larger?

**A.** Currently the game is still under development so there's not much sense in writing huge mods, as the upkeep of those would be nearly impossible with the speed the game is changing. I am still learning how to mod this game, but my plan is to introduce many different mods, mostly focusing on increasing the challenge of the game as well as improving QoL. This is a first dip in the waters for me.

---

## Changelog
* `Difficulty settings - trading`
	* `Sell multiplier` max value increased from 1.0 to 5.0
	* `Items amount` max value increased from 5.0 to 10.0
	* `Traders money` max value increased from 5.0 to 10.0
	* `Price: X` max value increased from 2.0 to 5.0
* `Difficulty settings - loot`
	* `Items amount` max value increased from 5.0 to 10.0
	* `Amount of single item` max value increased from 5.0 to 10.0
	* `NPC ammo amount` max value increased from 10.0 to 20.0
* `Difficulty settings - progression`
	* `Character health` min value decreased from 40.0 to 1.0
	* `Character health` max value increased from 120.0 to 500.0
	* `Minimum transportable weight` min value decreased from 5.0 to 1.0
	* `Minimum transportable weight` max value increased from 30.0 to 150.0
	* `Hunger/thirst decay rate` max value increased from 2.0 to 5.0
	* `Reputation multiplier` max value increased from 4.0 to 10.0
	* `Skill experience multiplier` max value increased from 4.0 to 10.0
	* `Reputation from quests` max value increased from 4.0 to 10.0
	* `Roubles from quests` max value increased from 4.0 to 10.0
	* `Items from quests` max value increased from 4.0 to 10.0
	* `Service price` max value increased from 2.0 to 5.0
* `Difficulty settings - enemies`
	* `Human health` max value increased from 2.0 to 5.0
	* `Human damage dealt` max value increased from 2.0 to 5.0
	* `Mutant health` max value increased from 2.0 to 5.0
	* `Mutant damage dealt` max value increased from 2.0 to 5.0
* `Heartbeat sound`
	* If max health is less than 40, heartbeat sound activates at below 50% health instead of below 20 health
