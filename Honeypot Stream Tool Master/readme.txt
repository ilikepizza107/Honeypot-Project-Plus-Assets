GIVEN:
Stream Tool
4 HTML-based overlays that use info inputted to the Stream Tool
-1 cam, asymmentric layout for dubs (tag, pronouns fields not used on dubs overlay)
-2 cam symmetric layout for singles
-commentary overlay
-vs screen, which can be used for VOD thumbnails

Non HTML-based graphics slides
-cam+game standby
-BRB

Add the HTML files to obs by dragging and dropping the files, or by adding a browser source
-SOURCE PROPERTIES TO CHANGE FOR EACH OVERLAY (https://github.com/Readek/Melee-Stream-Tool#setup-guide):
--turn on 'refresh browser when scene becomes active', another helpful one if you want to save computer resources 'shut down source when not visible'
--if the overlay looks weird, you can manually change the source dimensions to 1920 height 1080 width, or you can change your base canvas res to 1080p
--could also set 'use custom frame rate' option to the frame rate you stream at
if the overlays break at all feel free to dm me on discord: ilikepizza107#0001

Use the 'Project+ Stream Tool 1.0.0.exe' file to operate the scoreboard
-can turn on the intro in the settings in the bottom right
--intro gives a transition overlay with player names on first game, and round number after the first game
-DUBS: both players from 1 team should go into one of the player slots (Ex: johnny & jerry), other team goes into the other player slot 
-DUBS: color should match team color. tag, pronoun, and character field not used in dubs overlay

If you dont have custom transitions already, use the ones given in the folder Resources/OBS Transitions.
-Set these up as new stinger transitions in obs, and then set the transition point to 350 ms (https://github.com/Readek/Melee-Stream-Tool#setup-guide)
-You can set swoosh to be the default transition, and for certain scenes (singles, dubs, etc.) you can right click on the scene and set a transition override to game in
-If you want to have a second scene for flipped cams i heavily recommend an obs plugin called transition table so that you can have a cut transition between the regular and flipped cam versions of the scene instead of the stinger
--https://obsproject.com/forum/resources/transition-table.1174/