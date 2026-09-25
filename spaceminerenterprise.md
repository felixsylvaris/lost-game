# About
This is a vibecode  game, by default HTML .js; Tiny project. 
The story: We run space mining company. We manage crew, equipment, sell our goods. 
Gameplay: It is spreadsheet simulator with tetris puzzle mining and procesing. 
Inner layer: This is  a boardgame which could be given to High school econ classes to teach students how to run business, at least principles. Some business expenses could have game world names, like instead of paying taxes, we pay space company license. 

Goal of project: Is to make business simulator which is very businessy. Useful educational tool.
Goal of game: Get better cash flow than anthropic. 

Features (mostly future feature):
* Workers, paying them, training, hiring. Tentacle fridays. 
* Equipment, maintanence. 
* General base work, clean, cook. 
* Admin and HR cost? Security cost is just another cost. Is battlecruiser tax deductable?
* Product decision, for starter which mineral to mine. 
* Loans, and other capital acquisition
* Maintaining clients and suppliers. 
* Possible vertical integration. 
* Shiftining to procesing
* Some RD or licensing
* marketing among smugglers to get new contracts

*Not yet designed:* Tetris minigame is not here. No romance with space margaret tacher yet. No API to compare our profit with ai frontier companies yet. 


# Minimal working version. 

## Workers pannel 
We have 4 workers, with names, and drop down list to role to assign them to. 
Roles: Miner Pilot*, Mechanic*, Stafer. 
*Miner Pilot is required to mine. 
* Mechanic is not literally requied, but there is chance drill shuttle breaks down each turn. 
Staffers do everything else, mostly cleaning, and cooking. 
Wage: Each worker has wage, minimal value is 5c. credit is universal cash unit. But we can put any number here. 

## Budget Panel
It calculates our turn costs. And 12turn costs. 12 is annual. 
Initially our cost are: wages, food, maintainence. 
Initially our profits are: selling ore. 

** Mining Panel
We have 10 asteroids to pick from. Each asteroid have 1 resource, present deposit, ease (of extraction)
Each have resource type: Water (low cost, high demand, mass) , Silica, Carbon (high demand, mass) , Heavy, Rare (rare, expansive, shallow) . 

In mining panel we also have list of drill vessels (1). And drop down list which asteroid we wanna mine today. The game should remember our pick for next turn. But we can always change it. 
Drill Vessel mines 10 units * ease, round up. 

** Sell panel
We can have monthly trades. Sell, buy. Buy after sell. We can only buy when we have cash. 
Or emergency trade 
We generally Buy food and parts, and sell ore. 

There is also temporary button "Get Space Union Funds" Which adds 10k.c. But this is more cheat code to not constantly bancrupt when we are trsting. 





