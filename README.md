# Practice_ProjectJS

Some modifications and simplifications was made to make it suitable for multiplayer.
I factorized player and enemy tanks code in a class named Tank (this is the renamed EnemyTank Class from phaser example code) since in multiplayer mode enemy tanks are just remote players.
creation and update code was moved to Tank class.

also added a Tank.kill method to remove a tank from game scene and moved the fire() code to Tank.fire