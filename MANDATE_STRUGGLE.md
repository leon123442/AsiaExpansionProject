# Mandate of Heaven

## Overview
The Mandate of Heaven is represented by a struggle that represents the reign and dissolution of a single dynasty. As with traditional Chinese historiography, the end of the struggle (with the fall of one dynasty) will immediately trigger a new struggle focused on its successor - the passing of the Mandate of Heaven.

The general struggle contains two phase cycles (see: **Phases**) that work in parallel. The first cycle represents the fluctuating stability of the ruling dynasty, while the second represents the conflicts that typically follow its collapse (or, occasionally, interruptions). Should a new dynasty successfully unite China, it will activate a decision that will restart the struggle.

## Related
- [This dev diary, on struggle modding ](https://forum.paradoxplaza.com/forum/developer-diary/crusader-kings-3-dev-diary-94-anatomy-of-a-struggle.1522115/)
- [CK3 Wiki, with vanilla struggle details](https://ck3.paradoxwikis.com/Struggle)

## Start and Ending
At the start of the struggle, the phase will be set to *Mandated by Heaven* (see: **Phases**). The emperor of China will receive an event that grants a timed modifier to help consolidate their rule. This will differ at game start; the holder of the Chinese Empire title will be the Emperor of China (Tang in 867, Song in 1066/1178), while the phase will depend on historical events (*Precious Harmony* due to the instability caused by the An Lushan rebellion for 867, *Mandated by Heaven* for 1066, and *Precious Harmony* due to the Jin-Song split in 1178).

The struggle will end, as with both vanilla struggles, by the de facto ruler of China selecting a decision. This will result in the end of the struggle (granting rewards/modifiers) and the start of a new cycle. The requirements of the decisions, and rewards for taking it, are as follows:

**Requirements**
1. No other involved or interloper character holds an Empire-tier title
2. Control most (90%?) Chinese counties (Chinese culture & in the North, Northwest, and South China `geographical_region`s, which roughly covers the 18 provinces), including:
    - 2 x Ancient Capitals: Chang'an, Luoyang
    - 4 x "Geographic Breadth": Chengdu, Mt. Tai, Nanhai, Jiankang/Nanjing
3. Legitimacy is at least 4
4. Level of Fame is at least Illustrious
5. Have positive opinion by all powerful vassals
6. Be in the *Precious Harmony* phase

**Rewards**
- 10000? prestige
- 5000? renown
- A timed modifier, with the following effects:
    - MaA Upkeep Reduction?
    - Vassal Opinion?
- Heroic legend seed, if DLC feature owned
- Unlock the Chinese Empire title

## Participants
Struggles in CK3 have 3 levels of participation: Involved, Interloper, and Uninvolved (everyone else, basically). When a character joins the struggle (Uninvolved --> Involved or Interloper), they will receive an event that allows them to adopt a Chinese culture or faith.

## Phases
The struggle contains 5 phases, each of which are described below. The flow chart shows all possible transitions and a rough explanation of each.

TODO Flowchart


### *Mandated by Heaven*
This phase represents the stable, legitimate, and ordained rule of a single dynasty. Historical examples include the Han (between the Han-Xiongnu War and Wang Mang), early Tang (before An Lushan), and Northern Song.

#### On Start
- No effects.

#### Modifiers
- Increased income/development
- Improved opinions
- Cultural acceptance

#### Transitions and Catalysts
- To *Wind and Rain*: Time; low legitimacy; plagues; war defeats; revolutions; other empires on de jure territory; low vassal opinion; emperor replacement by means other than natural death; death of the emperor when China both is feudal and has a multiple-heir succession law
- To *Shared Defiance*: Significant Non-Chinese Empire presence on de-jure Chinese territory.


### *Precious Harmony* (from 以和为贵, [The Analects, Xue Er](https://ctext.org/analects/xue-er/ens))
This phase represents economic development and relatively friendly but fragile relations between potentially multiple Chinese states. Historical examples include Southern Song, Tang after the An Lushan rebellion, and the most stable years of the Three Kingdoms. Similar to Conciliation/Compromise from Iberia and Stabilization from Iran.

#### On Start
- No effects.

#### Modifiers
- Longer truce duration
- Improved alliance acceptance?
- Improved personal scheme chance

#### Transitions and Catalysts
- To *Mandated by Heaven*: Time while reunified by former emperor only!
- To *Wind and Rain*: Hostile schemes; using hooks; reducing relations/opinion (e.g. rivalry)
- To *Shared Defiance*: Significant non-Chinese invasions (no land-holding required); Non-Chinese Kingdoms/Empires presence on de-jure Chinese territory.


### *Wind and Rain* (from 风雨飘摇, [Book of Poetry, Odes Of Bin, Chi Xiao](https://ctext.org/book-of-poetry/chi-xiao/ens))
This phase represents tense military buildup and scheming, but before significant conflict. A historical example is the majority of the Three Kingdoms period. Similar to the Opportunity phase from Iberia.

#### On Start
- If transitioning from *Mandated by Heaven*, this represents a significant hit to the dynasty's legitimacy, resulting in rebellions. All of the emperor's direct Kingdom/Duchy-tier vassals will receive a choice to: 1) Remain a vassal, 2) Declare full independence (resulting in a war with the emperor), or 3) Ask for autonomy (independence with a negative modifier but no war).
    - The probability of each will depend on opinion, military strength, and title tier (holders of kingdom titles will be much more likely to declare independence, for example).
    - The emperor may choose to decline choice 3, which will force the vassal to pick 1 or 2.
    - As there may be many vassals, the events will be staggered over several years with the strongest generally sooner, and the weaker vassals later. Additionally, the weaker vassals will be less likely to ask for autonomy, instead allying with an existing independent character or remaining in the empire.

#### Modifiers
- Scheme success chance
- Claim fabrication
- Scheme unlocks (abduction, claim throne, etc.)
- Cheaper armies

#### Transitions and Catalysts
- To *Weapons Drawn*: Hostile schemes; acquiring casus belli; using hooks; war declarations 
- To *Precious Harmony*: Friendly interactions; Good personal schemes; gifts; improving opinion (e.g. friends); alliances
- To *Shared Defiance*: Significant non-Chinese invasions (no land-holding required); Non-Chinese Kingdoms/Empires presence on de-jure Chinese territory. This transition is difficult to represent internal instability.

### *Weapons Drawn* (from 剑拔弩张, common saying)
This phase represents open warfare between Chinese states. Historical examples include the warring portions of the Three Kingdoms, Warring Kingdoms, 5 Dynasties and 10 Kingdoms, and so on. Similar to Hostility and Unrest phases from Iberia/Iran respectively.

#### On Start
- No effects.

#### Modifiers
- Lowered income/development
- Military bonuses (army size, maintenance, etc.)
- Lowered truce duration

#### Transitions and Catalysts
- To *Precious Harmony*: Friendly interactions; peace deals

### *Shared Defiance* (from 同仇敌忾, [Book of Poetry, Odes Of Qin, Wu Yi](https://ctext.org/book-of-poetry/wu-yi1/ens))
This phase represents a reaction to an external enemy, such as (but not limited to) the Mongol invasion. This phase is not in any particular cycle, and instead serves as a way to temporarily "unify" China against an external invader when its constituent states are happy. Historical examples are rare, but include the Chinese United Front during WW2 and Shun "attempts" to co-rule with Ming during the Manchu invasion. Note that this phase will be quite difficult to get to, and by the time it arrives, it will often be too late. 

#### On Start
- No effects.

#### Modifiers
- Improved alliance acceptance
- Improved personal scheme success chance
- Defensive bonuses
- Culture/Faith conversions

#### Transitions and Catalysts
- To *Precious Harmony*: Conquest of Chinese lands; peace deals; conversions