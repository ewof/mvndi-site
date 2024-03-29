# War

**For reference on how the wars operate, please look at this link below.**

[Towny Event War](https://townyadvanced.github.io/eventwar.html)

This page assumes you have read and understand the contents of link above.


Mvndicraft currently only has 4 of the 5 wartypes in Event War as currently the "World War" type is under development.

## Obtaining Tokens
One token is added to each town, once every Towny Day. (24 hours)

## Declaring War
In order to declare war you must redeem a War Declaration using your war tokens.

Using these commands you can redeem tokens for your town/nation.

> /t redeem token <war_type></br>
> /n redeem token <war_type>

And to declare war, with a war declaration in your hand.

> /declare war <war_type> <town/nation>

### Valid War Types
- riot
- townwar
- civilwar
- nationwar

### Declaration Permissions
- Residents are allowed to declare riots.
- Mayors are allowed to declare town and civil wars.
- Kings are allowed to declare nation wars.

## General Settings
- Block HP: ON
	- TownBlock HP: 18
	- HomeBlock HP: 36
		- Block HP will tick once every 5 seconds when considered active.
- Mayor/King Death: OFF
- Startup Delay: 10 minutes
- Points Per Kill: 5
- Fire Spread: ON
- Explosions: ON
- Economy: ON
	- Death Cost: $50
	- TownBlock Loss Cost: $100
	- If a town runs out of money during a war, they are removed from the war.
- Points
	- TownBlock: 10 (Awarded when a townblock is won)
	- Town: 20 (Awarded when a town is knocked out of a war)
	- Nation 100 (Awarded when a nation is knocked out of a war)

## War Type Specific Settings
### Riot
- Token cost: 5
- Minimum Required Players: 2
- Duration: 30 minutes
- Cooldown: 5 minutes
- Base Spoils: $10
- Resident Lives: 3
- Mayor Lives: 2
- Switch Use: YES
- Item Use: YES
- Winner Takes Over Town: YES

### Town 
- Token Cost: 2
- Minimum Required Players: 3
- Duration: 1 hour
- Cooldown: 15 minutes
- Base Spoils: $100
- Resident Lives: 3
- Mayor Lives: 2
- Switch Use: YES
- Item Use: YES
- Winner Takes Over Town: NO

### Civil 
- Token Cost: 7
- Minimum Required Players: 4
- Duration: 2 hours
- Cooldown: 20 minutes
- Base Spoils: $500
- Resident Lives: 6
- Mayor Lives: 4
- Switch Use: YES
- Item Use: YES
- Winner Takes Over Nation: YES

### Nation
- Token Cost: 4
- Minimum Required Players: 5
- Duration: 3 hours
- Cooldown: 30 minutes
- Base Spoils: $1000
- Resident Lives: 9
- Mayor Lives: 6
- Switch Use: YES
- Item Use: YES
- Winner Conquers Towns: YES
