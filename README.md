# Light Anti-Cheat Windows
 Anti Cheat for Unity Games
 
 # Features
- Speed Hack Detection (still in work)
- Hardware logging
- Anti VM
- Verify the signature of the AntiCheat to detect changes
- Anti Debugger
- Scan For Suspicious Processes and strings in processes

 # How to Use
 1. Drag the Light Anti-Cheat prefab into your Scene
 2. Create a new Script and name it something like OnCheatDetected. In this
      class you want to add a Method called Detected. Now you can do whatever you want
      when a cheat was detected, for example kick the player out of the match.
3. Assign the method on the CheatDetectedEvent from the AntiCheatComponent script.
4. Build your game with Il2cpp.
5. Copy the Light Anti-Cheat.exe file into your build game folder.
6. Done!
