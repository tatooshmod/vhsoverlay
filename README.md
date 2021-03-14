So basically I was tired of making a vhs overlay so i made a script that did it for me

## Actual description
    When you run the script, it'll ask you for info on the overlay, (play/pause, counting up or down, length the overlay runs for, date, etc.) and then it'll create an image sequence of all the overlays in ./img/ for you to import into your favourite software as an image sequence like kablamo kabloomo and it's done

## Requirements
    Bash
    ImageMagick
    Zenity

## Slightly in-depth description:
    So you can either just run it from your file viewer, or from the command line, the downside of running it from the command line is that it outputs random crap that i used for debugging. It also creates two directories, inside of the same directory the script is in. ./assets/ holds the assets that the script uses (they get downloaded automatically isnt that fancy) and ./img/ will hold the outputted images. If you end up changing the script, don't mind my silly comments on LITERALLY EVERY LINE

## Fair warning
    This is the first actually useful script i've written, so i'm pretty excited
    (by the way if you want to edit the code to change it around thats fine just dont steal it thanks)