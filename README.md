# PoD-Things
# qordsfilter.filter

Thanks for checking out my filter! Before you get too far into this, it would be a great idea to get a good grasp on the basics of using a filter, and using multiple filters. Most of the filters do the same things, but in different ways and with different looks. I always reccommend new players download multiple filters and try them all; it's so easy to switch in-game that there's no reason not to. 

This filter was created to filter things out as you level as well as give you the option to make it more strict along the way. 

Level-based filtering:
The final lones in the filter control the level-based filtering action, you can disble any of those rules by commenting them out (adding // in front of the line so they are ignored)
    If you're under level 31, show all pelts, barb helms, necro shields & wands, sorc orbs, staves, and scepters with more than 1 socket
    If you're under level 60 and filterlevel is less than 4, show all magic and rare aweapons and armor 
    If you're under level 40, show all non-etheral and non-inferior weapons and armor that have more than one socket 
    If you're under level 60, show all 4 socket weapons that are eth and not inferior 
    If you're between levels 40 and 80, show all exceptional and elite weapons and armor that are not eth and not inferior and have more than 1 socket 
    Hide all inferior weapons and armor 
    If you're under level 19, show eth and non eth weapons and armor, and tell us if they have sockets 
    If you're above level 18, hide all other weapons and armor 

That last line will hide anything not explicitly allowed to show by a line above it. 

Filterlevel based strictness:
There are 5 levels of strictness in this filter, you can switch between them from the menu in game. 
Filterlevel 1: The loosest setting
Filterlevel 2: Hides some utility items like thawing (also hidden after level 60) and stamina (also hidden after level 42) pots, lower tier gems, some blue (magic) items
Filterlevel 3: Hides the above, as well as:
    Lower runes (except Ort)
    Large charms
    Some of the more common runeword bases like 4/5 os flails
    Some class specific magic items 
        # Need to revisit this now that crafting has opened up
    $35k throwing weapons

Filterlevel 4: Same as above but
    Shows all those lower runes
    Hides some lower set and unique items
    Many items whose numbers of sockets was shown in grey
Filterlevel 5: Strictest
    Any item whose sockets were shown in grey (most tan socketed items remain visible)


To be continued...



