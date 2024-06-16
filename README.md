[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282666&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   open the browser and search for visual studio code
   click on the first link and you will be able to see the green download button for window and click on it to download the file.
   agree with the licence terms and condition.
   click on next and choose the options you need .
   Then click on the installation button which takes a few seconds.
   when the visual studio code is installed has been finished you can click the launch button and click on finish button. 


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   settings:
   1. Theme and icon
   Color theme: Go to 'file> Preference> Color Theme' and choose a theme that suits you.
   File Icon theme: Go to 'File> Preference> file Icon Theme' and select an icon set like "Material Icon Theme"
   2. Font settings:
   Open File > Preferences > Settings and search for font.
Adjust Editor: Font Size to your preferred size.
Choose a coding-friendly font like "Fira Code" or "Source Code Pro" and enable ligatures if desired by setting Editor: Font Family and Editor: Font Ligatures.
3. Auto-save
In settings, search for auto save and set it to afterDelay or onWindowChange.

2. Essential Extensions
Code Completion and Linting:

ESLint: JavaScript/TypeScript linting.
Prettier - Code formatter: Code formatting.
Python: Linting, IntelliSense, Jupyter support for Python.
C/C++: IntelliSense, debugging, and code browsing for C/C++.
Version Control:

GitLens: Enhances the Git capabilities within VS Code.
Git Graph: Visualizes the repository's commit history.
Languages and Frameworks:

HTML CSS Support: For better HTML and CSS development.
Live Server: Launch a development local server with live reload feature for static & dynamic pages.
Java Extension Pack: For Java development.
Ruby: For Ruby development.
Django: For Django framework support in Python.
Productivity:

Path Intellisense: Autocompletes filenames.
Bracket Pair Colorizer 2: Colors matching brackets.
Todo Tree: Manages TODO comments.
Debugger:

Debugger for Chrome: Debug JavaScript code in the Chrome browser, or any other target that supports the Chrome Debugging Protocol.
Python Extension Pack: Debug Python applications.
3. Keyboard Shortcuts
Customize shortcuts by going to File > Preferences > Keyboard Shortcuts.
Popular shortcuts include Ctrl+P for quick file open, Ctrl+Shift+P for the command palette, and Ctrl+Shift+X for the extensions marketplace.
4. Terminal Configuration
Go to File > Preferences > Settings and search for terminal.
Set your preferred integrated terminal (e.g., Bash, PowerShell).
5. Snippets
Create custom code snippets by going to File > Preferences > User Snippets.
6. Workspace Settings
Open settings (Ctrl+,) and use the gear icon to set workspace-specific settings.
Useful for project-specific configurations.
7. Sync Settings
Use the Settings Sync feature to synchronize your settings across multiple devices.
8. Extensions for Specific Languages
JavaScript/TypeScript: ESLint, Prettier, Path Intellisense.
Python: Python, Pylance, Jupyter.
C/C++: C/C++, CodeLLDB or C++ Intellisense.
Web Development: HTML CSS Support, Live Server, IntelliSense for CSS class names in HTML.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   1. Main Bar; located at the top of the window and it contains menus like File, Edit, View, Go, Run, Terminal which provides a list of actions that you can perform within VS code.
  2. Editor Group: is the central workspace where you write and edit your code.
  3. Status Bar; located at the bottom of the window. Provides information on the current file you are working on, the language mode and the status of current extensions like Git integration.
  4. Command Palette; allows you to execute various commands and actions quickly by typing their names.
  5. Tabs; located above the editor pane, tabs represent the open files. You can easily switch between different files by clicking on their respective tabs
  6. Quick Open; allows you to quickly search for and open files within the workspace.
  7. Activity Bar; positioned on the side, it consists of different icons representing various views like explorer, search, source control, Debug, and Extension.
  8. Side Bar; found on the left side of the windows and include the explorer view by default, displaying your project structure, files and folders.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   command Palette is accessible using the 'Ctrl+Shift+P shortcut.
   It allows you to execute various commands and actions quickly by typing their names.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions in VS Code play a crucial role in tailoring the editor to specific needs, adding language support, tools, theme and more.

   Finding and installing Extensions in VS Code
   1. Via the Extension view
   - Click on the extensions icon in the activity bar on the sidebar of VS Code.
   - Search for extensions by typing in the search bar.
   - Click on the install button for the extension you want to install
   Managing extensions
   1. Disabling or uninstalling Extensions.
   in the extensions view, disable or uninstall extensions by clicking on the gear icon next to the extensions name.
   2. Settings
   some extensions have settings that can be configured by going to File> Preferences > settings and then searching for the extension setting.

   Examples of Essential for web Development
   1. ESLint
   Helps maintain code quality by highlighting syntax and style issues in your JavaScript/TypeScript code.
   2. Prettier
   Provides code formatting for a variety of file types, ensuring consistent code style across the team
   3. Live Server
   Launches a local development server with live reload feature for static and dynamin pages.
   4. Path Intellisense
   Autocompletes filename in your code to avoid spelling errors and make it easier to navigate your project.
   5. color Highlight
   Shows the colors corresponding to there hex codes or color name.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   Opening the integrated Terminal:
   1. Open Visual Studio Code, launch VS Code on your machine.
   2. Access the integrated Terminal by
   - press 'Ctrl +"(backtick) on windows
   go to the menu and navigate to view terminal
   - click on the '+' icon at the top left corner of the sidebar and select 'New Terminal'

   Using the integrated Terminal:
   1. Navigating the Terminal; you can navigate just like a regular terminal using commands like 'cd' to change directories.
   2. Running commands; you can run any command supported by your system directly in the integrated terminal.
   3. Customizing; The integrated terminal supports customization through settings where you can change the shell type , font size, colors 

   Advantages of using the Integrated Terminals vs External Terminal:
   1. seamless integration; the integrated terminal is built directly into VS Code, providing a seamless development experience without the need to switch between different applications.
   2. Workflow Efficiency. You can easily switch between editing code and running commands in the terminal , saving time and effort.
   3. Context Switching; with the integrated terminal, there is no need to switch back and forth between the editor and a separate terminal window, maintaining your workflow.
   4. Customization; you can customize the integrated terminal to suit your preferences, making it comfortable to work with.
   5. Multiple Terminals; VS Code allows you to open multiple terminals within the same window, which can be helpful for various tasks simultaneously

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

Creating Files:

From the Explorer:

Open the Explorer view by clicking the Explorer icon in the Activity Bar or pressing Ctrl+Shift+E.
Right-click in the Explorer view and select New File or use the New File button at the top of the Explorer pane.
Type the file name and press Enter.
Using the Command Palette:

Press Ctrl+Shift+P to open the Command Palette.
Type >File: New File and press Enter.
Creating Folders:

From the Explorer:
Right-click in the Explorer view and select New Folder or use the New Folder button at the top of the Explorer pane.
Type the folder name and press Enter.
Opening Files and Folders
Opening Files:

From the Explorer:
Simply click on a file in the Explorer view to open it.
Using Quick Open:
Press Ctrl+P to open the Quick Open prompt.
Start typing the name of the file and select it from the list that appears.
From the Command Palette:
Press Ctrl+Shift+P to open the Command Palette.
Type >File: Open File and navigate to the desired file.
Opening Folders:

From the File Menu:
Go to File > Open Folder and navigate to the desired folder.
Using the Command Palette:
Press Ctrl+Shift+P to open the Command Palette.
Type >File: Open Folder and navigate to the desired folder.
Navigating Between Files and Directories
Explorer View:

Use the Explorer view (Ctrl+Shift+E) to see and navigate your project's file and folder structure.
Click on folders to expand or collapse them.
Use the breadcrumbs at the top of the editor to navigate back through the directory structure.
Quick Open (Ctrl+P):

Press Ctrl+P and start typing the name of the file you want to open.
Use : followed by a line number to jump directly to that line (e.g., index.js:10).
Command Palette (Ctrl+Shift+P):

Press Ctrl+Shift+P and start typing commands related to files and navigation, like >Open File, >Open Recent, or >Navigate.
Sidebar and Tabs:

Use the sidebar to switch between different views (Explorer, Search, Source Control, etc.).
Use the tabs at the top of the editor to switch between open files.
Go to Definition and References:

Use F12 to go to the definition of a symbol (function, variable, class, etc.).
Use Shift+F12 to find references to a symbol.
Breadcrumbs:

Enable breadcrumbs by going to View > Show Breadcrumbs.
Use the breadcrumbs at the top of the editor to navigate through your file structure and symbols.
Keyboard Shortcuts:

Navigate Back/Forward: Ctrl+- to navigate back and Ctrl+Shift+- to navigate forward.
Toggle Sidebar: Ctrl+B to toggle the sidebar visibility.
Open Recent Files: Ctrl+R to open the list of recently opened files.
Multi-root Workspaces:

Open multiple folders in a single workspace by going to File > Add Folder to Workspace.
Save the workspace configuration by going to File > Save Workspace As.
Managing Files and Folders
Renaming Files/Folders:

Right-click on the file or folder in the Explorer view and select Rename.
Type the new name and press Enter.
Moving Files/Folders:

Drag and drop the file or folder within the Explorer view to move it.
Use cut (Ctrl+X) and paste (Ctrl+V) to move files and folders.
Deleting Files/Folders:

Right-click on the file or folder in the Explorer view and select Delete.
Confirm the deletion in the prompt.
File Search:

Use Ctrl+Shift+F to open the Search view.
Type your search query to find files and content within files.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   In VS Code users can find and customize settings in several wats like:
    Accessing Settings
   a) Using Command Palette
   open the command palette by pressing 'Ctrl+Shift+P for windows
   type preferences: Open Settings and select it to open the settings UI
   b) via menu
   - click on 'File' in the menu bar.
   - select 'preferences'
   - click on settings to open the settings UI
   Customizing settings
   1. changing the theme
   - Open the settings UI using one of the methods above
   - in the search bar at the top, type 'color theme','Edit in settings.json 'link.
   - Under 'Preferences: Color Theme'click on the 'Edit in settings.json' link.
   - in the '"workbench.colorTheme"'
   setting, change the value to your desired theme
   2. Changing the Font size
   - open the setting UI
   - in the search bar, th
   ype "'font size'"
   - you can adjust the font size in the following waus
   . For the entire editor: Find the '"editor.fontSize"' setting and change the value to your desired font size.
   - For the terminal: Find the '"terminal.intergrated.fontSize"' setting and change the value.
   3. Changing Keybindins:
   - open the setting UI.
   - in the search bar type "'keybindings'
   - click on the 'Keybindings' link to edit keybindings.
   - you can customize keybinding in two ways:
   1. Editing keybindings.json directly:
   - click on the 'keybindings.json 'link to open the keybindings in the JSON format.
   2. Reassigning keybindings i settings:
   - Go back to the settings UI
   - search for the specific action you want to reassign a key


   

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   1. Install Required Extensions
Ensure you have the necessary extensions installed for your programming language. For example:

Python: Install the "Python" extension.
JavaScript/TypeScript: The built-in Node.js debugger.
C/C++: Install the "C/C++" extension.
2. Open Your Project
Open the project folder that contains your source code by selecting File > Open Folder or using Ctrl+K Ctrl+O.

3. Create a Launch Configuration
Open the Run and Debug View:

Click on the Run and Debug icon in the Activity Bar on the side of the window or press Ctrl+Shift+D.
Add a Configuration:

Click on create a launch.json file link. This will open a launch.json file inside a .vscode folder in your project.
Select the environment for your program (e.g., Node.js, Python, etc.).
VS Code will generate a default configuration. Customize this configuration as needed.
Set Breakpoints
Open the file where you want to set a breakpoint.
Click in the gutter to the left of the line number where you want to break. A red dot will appear indicating a breakpoint.
5. Start Debugging
Go to the Run and Debug view (Ctrl+Shift+D).
Select the configuration you want to use.
Click the green play button to start debugging.
Key Debugging Features in VS Code
Breakpoints:

Set breakpoints by clicking in the gutter next to the line numbers.
Conditional breakpoints can be set by right-clicking on an existing breakpoint and selecting Edit Breakpoint....
Watch Variables:

Add variables to the watch list to keep track of their values during debugging.
Go to the Run and Debug view, and in the WATCH section, click the + icon to add a variable.
Call Stack:

View the call stack to see the sequence of function calls that led to the current point of execution.
The call stack is available in the Run and Debug view under the CALL STACK section.
Variable Hover:

Hover over variables in your code to see their current values.
This feature is useful for quickly inspecting variable values without adding them to the watch list.
Step Through Code:

Use the following controls to step through your code:
Continue (F5): Resume program execution.
Step Over (F10): Execute the next line of code but do not step into functions.
Step Into (F11): Step into the function being called.
Step Out (Shift+F11): Step out of the current function.
Restart (Ctrl+Shift+F5): Restart the debugging session.
Stop (Shift+F5): Stop debugging.
Debug Console:

Evaluate expressions and interact with the debugger.
Access the Debug Console from the Run and Debug view.
Exception Handling:

Configure exception handling by modifying the launch.json file.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    1. Installing Git
Make sure you have Git installed on your system. You can download it from git-scm.com and follow the installation instructions.
2. Initializing a Repository
Open Your Project:

Open your project folder in VS Code by selecting File > Open Folder or using Ctrl+K Ctrl+O.
Initialize Git Repository:

Open the Source Control view by clicking the Source Control icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+G.
If your project folder is not already a Git repository, you’ll see an Initialize Repository button. Click on it to initialize a new Git repository.
3. Making Commits
Stage Changes:

In the Source Control view, you will see all your changes listed under Changes.
Hover over the file you want to stage and click the + icon that appears, or stage all changes by clicking the + icon next to Changes.
Commit Changes:

After staging your changes, enter a commit message in the message box at the top of the Source Control view.
Click the checkmark icon or press Ctrl+Enter to commit the staged changes.
4. Pushing Changes to GitHub
Add Remote Repository:

If you haven’t already, you need to add a remote repository (e.g., on GitHub).
Open the terminal in VS Code by selecting Terminal > New Terminal or pressing Ctrl+ (backtick).
Add the remote repository using the command,
Push Changes:

Push your commits to the remote repository by clicking the ... (More Actions) icon in the Source Control view and selecting Push.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
plp academy notes
AI assistant
- Submit your completed assignment by 1st July 

