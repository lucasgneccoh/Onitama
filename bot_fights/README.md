# Create a tournament
See the [example file](https://github.com/lucasgneccoh/Onitama/blob/main/bot_fights/tournament_example.json) and follow the syntax. You can run multiple tournaments with one file. 
The name of the tournament will be used in the name of the file with the results.
The `bot` attribute must always be present and correspond to a valid bot key (See [play_functions](https://github.com/lucasgneccoh/Onitama/blob/main/modules/play_functions.py) for the dictionary of available bots)
Be careful with the attributes you pass to each bot. For the moment, passing wrong arguments (or extra arguments) results in an error. The match will still run, but without results.
