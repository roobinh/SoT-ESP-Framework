### When I run the hack, nothing shows up
If you JUST run the hack as-is without changing any code, you should **only** see a player count at the top right
of the window. You MAY need to change where that is being displayed on the screen dependent on your monitor size. To
change that position in the main.py file. There are more features mentioned in the readme.md, but there is work required
to get there also mentioned in the readme.md (Prerequisites section)

Check the following:
1. By default, it works for the Microsoft version of the game, there is a variable to toggle if you are using Steam. 
   Does this apply to you?
2. Validate you have a pygame window that is opening and there are no errors in the python window
3. Have you made sure all of your window sizes have been updated according to the readme?
4. Have you corrected the tests of faith mentioned in the readme.md (Prerequisites section)?
5. Are you running in windowed mode?