Talk to the Wizard - Project Summary
Project Overview
Talk to the Wizard is a short, interactive narrative experience built in Unity. The player encounters a mysterious wizard and must choose how to respond to his greeting. The goal of the game is to demonstrate a branching dialogue system where player choices affect the outcome of the interaction. This simple project showcases fundamental Unity UI systems, player interaction via buttons, and basic dialogue logic.
Controls
- Mouse Click: Select one of the dialogue response buttons.

There are no movement or combat controls. The entire experience is driven through the UI and choice selection.
Character Behaviors
NPC (The Wizard):
 - Displays a single line of dialogue: 'Welcome, traveler! What do you seek?'
 - Waits for the player to respond with one of three options: Wisdom, Power, or Riches.
 - After selection, the wizard responds with a line reflecting the player's choice.

 Player:
 - Interacts only through button selections.
 - Cannot move or explore—this is a fixed camera, dialogue-focused scene.

 There are no enemies in this project, as it is focused solely on interaction and branching text-based choice.
Project Duration
The full project took approximately 2 days to complete, including:
Day 1:
 - Setting up the Unity UI (1.5 hour)
 - Writing and integrating the dialogue system (2 hours)
Day 2:
 - Testing, polishing, and major UI layout adjustments (3 hours)
 - WebGL build and deployment (1 hour)
Challenges Encountered
The most challenging part was ensuring clean handling of button listeners so that each choice triggers the correct outcome. Unity UI button event handling can retain previous listeners between play sessions if not cleared properly, which could result in unexpected behavior. Additionally, sizing and aligning the dialogue box and choice buttons for readability across different screen resolutions required some UI tweaking.
Conclusion
Talk to the Wizard is a simple yet effective example of how dialogue systems can be implemented in Unity without third-party tools. It forms the foundation for more complex branching storylines or RPG-style NPC interactions. This project taught essential skills in UI setup, C# scripting, and interactive narrative design.

