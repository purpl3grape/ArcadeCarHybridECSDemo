<b>UNITY VERSION: 2018.3.0f2</b><br>

# ArcadeCarHybridECSDemo
Arcade Car Physics using Hybrid ECS and some Pure ECS approaches in the Demo
<br>Created: 20181226
<br>
<br>SETUP INSTRUCTIONS<br>
<br>Select a scene and hit Play.
<br>
<br>
<br><b>Only in case of any setup errors:</b>
<br>
<br>[1] Go to /Scenes/ArcadeCarHybridECS.scene
<br>[2] PC input: Disable LogitechInitialize.cs on the 'spawner' gameobject. Then hit Play.
<br>[3] LogitechG920Wheel Input requires the 'LogitechSteeringWheelSDK_8.75.30.zip' SDK @ https://www.logitechg.com/en-ca/partnerdeveloperlab/sdk-resource-list/steering-wheel-sdk.html
<br>[4] Copy 'LogitechSteeringWheelEnginesWrapper.dll' to: \ArcadeCarHybridECS_Template\Assets\LogitechSDK\Lib\GameEnginesWrapper\x64
<br>[5] Copy 'LogitechSteeringWheelLib.lib' to: \ArcadeCarHybridECS_Template\Assets\LogitechSDK\Lib\x64
<br>[6] Select Scene, and hit Play
<br>
<br>TODO:
<br>To implement a path finding system to move many units at once which is currently based off the pure-ecs-physics project
