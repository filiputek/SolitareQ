# SolitareQ
Solitare. Why Q? I have no idea.
## requirements
Python installed (from https://www.python.org/downloads/)
<br>
Optional: a terminal/cmd able to process ANSI escape charaters (e.g. cmd in windows 11)

## installation
at first, download and unzip a compressed folder which you've downloaded.
then go to the location where folder have been unzipped and open a shortcut called Solitare.
If shortcut doesn't show, navigate to the game_files folder and open file main.py.
If doesn't work, open terminal/cmd and navigate to the game_files folder. Then type "python -m main"

## game rules and mechanics
Press enter to stare playing.
All rules are explained in game after using commands "help", "help rules" and "help [command name]".

## project documentaion
purpose of every function is explained in code in comments
Purpose of every .py file: 
    <br>
    * main.py - the main progrem of the game. It calls commands from another programs and  executes commands given by user 
    <br>
    * logics.py - file contaning definitions of classes and enums
    <br>
    * input_manager.py - module reading input from user, preparing it for further usage and filling optional arguments in commands
    <br>
    * input_sanitizer.py - file veryfying are commands possible to execute 
    <br>
    * output_manage - module, which purpose is to manage output, respond to user and show them a current state of the game

<br>
<br>
Purposes of some other files:
    <br>
    * files in ascii_graphics folder - nothing to explain here, graphics printed on screen in certaing moments of the game
    <br>
    * files in help folder - texts to print when user requests an explanation of a certain subject
    <br>
    * command_formats.json - file saying what and how many arguments can every command take and how are they called

<br>
<br>
when naming things in my project, I sticked to the following case convention:
    variable, function and method names: camelCase
    constant names: ALL_CAPS_AND_UNDERSCORES_CASE (I don't know how is it called)
    class names: PascalCase
    file names: snake_case


# 
Players, have fun! 
People reading my code, have fun! (can be a little harder)
