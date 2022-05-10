# Games-Engine-2-Assignment
Name : Ishaan Rawat 

Student Number : C18459302

## Description
- This project is a simple space battle created using Unity in order to demonstrate the steering behaviours utilized throughout the semester.
- All of the spaceships' movements are controlled by certain behaviours.
- These behaviours include path following, steering, obstacle avoidance, fleeing, pursue, offset pursue, arrive and seek.
- All models were imported through the Unity Asset Store.

## Events
1. Main Ship begins moving using path script behaviour following gizmos.
2. Main Ship avoids asteroid using obstacle avoidance script.
3. Main Ship collides with a 3D invisible trigger which activates the second scene.
4. Enemy Ship is captured in the scene moving closer to the mine object using seek behaviour.
5. This hits another trigger which activates onCollide method causing for a scene change.
6. Third scene activated, Enemy Ship uses seek script to attack Main Ship.
7. Main Ship uses follow path script to run away and eventually hit final trigger for final scene.
8. Backup arrives wth smaller ships using offset pursue using the Main Ship as the leader. 
9. Main Ship hunts down Enemy Ship alongside mini ships.
10. Enemy Ship atempts to flee, pursuit in effect.

## Scene Snapshots
### Scene 1: 
![image](Assets/Snaps/scene1.JPG)

### Scene 2: 
![image](Assets/Snaps/scene2.JPG)

### Scene 3: 
![image](Assets/Snaps/scene3.JPG)

### Scene 4: 
![image](Assets/Snaps/scene4.JPG)


## Classes
| Class/asset | Source |
|-----------|-----------|
| SteeringBehaviour.cs | Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| Seek.cs | Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)   |
| Pursue.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| OffsetPursue.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| ObstacleAvoidance.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| FollowPath.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| Boid.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| Arrive.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| Path.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| Flee.cs| Reference [Source](https://github.com/skooter500/GE2-2021-2022/tree/master/GE2%202022/Assets)  |
| SceneOneSwitch.cs| Self-Written |
| SceneTwoSwitch.cs| Self-Written |
| SceneThreeSwitch.cs| Self-Written |


## References
### Spaceship 
-> https://assetstore.unity.com/packages/3d/vehicles/space/star-sparrow-modular-spaceship-73167#description

### Skybox 
-> https://assetstore.unity.com/packages/2d/textures-materials/diverse-space-skybox-11044#description

