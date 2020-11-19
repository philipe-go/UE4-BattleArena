# GAME ENGINE III - Assignment II

## Assignment 2 of Game Engine 3 

- ## done by Philipe Go.

    Remark: The game spawns enemies after 10 seconds if there is no enemy on the arena. A counter will be displayed showing when the next enemy will be spawned.
    if the player dies a menu will appear giving the option to retry or quit.

## Control:

- #### AWSD
move the player
- Left mouse button - melee attack
- Right mouse button - cast current magic
- Q | 1 & E | 2 - cast the magic and change current magic
- left shift - Run
- left ctrl - use health potion
- space bar - roll  

## Tasks

### Task 1

- #### Task: Done
- #### Bonus: Done  

### Task 2

- #### Task: Done
- #### Bonus: Done  

### Task 3

- #### Task: Done
- #### Bonus: Done  

    Remark: Use Q|1 or E|2 to change and cast magic type -  Magic 1 is a long range straight projectile - Magic 2 is an explosion ahead of the player with an offset of 400 units. It deals damage within a range of 500 units  

### Task 4

- #### Task: Done
- #### Bonus: Done

    Remark: Stamina is consumed when the player is running or performing a melee attack. If casting magic the MP is consumed instead. When the SP gets to 0 the player has do wait until its level recharges to 20%.

### Task 5

- #### Task: Done
- #### Bonus: Done  

    Remark: when drinking the potion the player can't run and roll but can walk. If any attack is trigged the drinking potion actio will stop in the middle without.

### Task 6

- #### Task: Done
- #### Bonus: Done  

### Task 7

- #### Task: Done
- #### Bonus: Done  

### Task 8

- #### Task: Done
- #### Bonus: Implemented but not working properly - node connection removed to avoid bugs

### Task 9

- #### Task: Done
- #### Bonus: Done
    Remark: Rage logic implemented on the BT_EnemyHybrid using the BlackBoard boolean "isRaged". In the BP_EnemyHybrid if the HP gets below 25% of initial HP the enemy enter on the rage state.  

### Task 10

- #### Task: Done
- #### Bonus: Done  
    Remark: There are 4 health potions on the arena and the enemy spawns a MP potion when dead. 
    The MP potion recovers MP when triggered. The player also recovers MP when he hits the enemy with a melee attack.
    The health potion is add to the inventory when triggered.
    


