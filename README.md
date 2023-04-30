# Learn-unity

# Installation
1. Install dotnet https://dotnet.microsoft.com/en-us/download
2. Install mono https://www.mono-project.com/docs/getting-started/install/
3. Install vscode https://code.visualstudio.com/download
4. Install **Unity Hub** https://unity.com/download

# Code completion setup
1. Run Unity Hub
   - That will guide you through installing **Unity Editor**. Install that.
   - Will take 15 minutes. Wait till done.
3. Create a new project from samples
   - On Unity Hub, click Projects -> New project
   - On the left side of the window, click on **Core**, then **2D Core**.
   - On the right hand side of the screen, give project name **flappy**
   - Hit **Create project** button. It will take a minute or two
   - It should open up a window with 5 panes
     - Hierarchy
     - Scene/Game (with Scene being chosen)
     - Inspector
     - Project/Console (with Project being selected)
     - Assets (actually a sub pane of Project)
   - Right click on the **Assets** window, do: **Create** -> **C# Script**
   - Name the script **whatever**
   - Hit **Command ,** to get into settings for **Unity Hub**
   - Modify **External Tools** -> **External Script Editor**. Choose **Visual Studio Code**
   - Double click on the script. That should open **Visual Studio Code**
     - It should offer you to install **C# Extention**. Install it.
     - While on vscode, hit **Command ,** to get into its setting
     - In the search area, type **modern**
     - See the item "**Omnisharp: Use Modern Net**" ? Unselect it
     - Hit **Command-Q** to exit vscode
     - Reload vscode by double clicking on **whatever** on Unity
     - On **whatever.cs** file look for **void Start()**
     - Insert a line before it.
     - Start typing **game**
     - It should pop up with suggestion including **GameObject**, **GamepadSpeakerOutputType** etc. That's how you know it's working
     

# Learn
1. Follow along https://www.youtube.com/watch?v=XtQMytORBmM
