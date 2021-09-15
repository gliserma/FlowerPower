# FlowerPower_Game
- A 2d gardening video game that teaches young children about primary and secondary colors
- Built in the Unity game engine with C#
- You will need to run the game from Unity 2020.3.3f1
- You will need Unity Hub to add this project

# Game Objective
- Fulfill the order in the upper left hand screen by harvesting the specified number of flowers of a given color

# Game Mechanics
- Drag a seed from the right UI and drop it into a plot. Note the number of seeds is limited.
- Right click the seed icon to cycle between different seed colors, which are all primary colors (red, blue, yellow)
- Flowers need water to grow. You can water a plot with the watering can. Rainy weather will also water the plots.
- Weeds will sap nutrients from any nearby flowers; cut them down with the scissors
- Plants (both flowers and weeds) will spread pollen to nearby plots, which might result in a new seed
- Two nearby flowers can cross-pollinate.
- Two primary colors will generate a secondary color.
- A primary color blended with its opposite secondary color will generate pests that eat flowers.
- Kill pests by isolating them, i.e. cutting down neighboring flowers that they could spread to.
- Harvest flowers by cutting them down when they are adults.

# Organization
- Code located in: FlowerPower_Game/Assets/Scripts/
- Art located in: FlowerPower_Game/Assets/Resources/
- Launch the game from the TitleScreen scene in: FlowerPower_Game/Assets/Scenes

# Next Steps
- Improve onboarding experience for new players by explaining the game mechanics within the game.
