# -sortf-file-and-folder-sorter-by-size.
an program for linux that sorts files and Folders by How big they are.

step 1)How to make it work?

so go to `/usr/local/bin` and typing `cd /usr/local/bin` into the terminal.
then,make the file "sortf" by typing `nano sortf` into taht directory.
then, open up the file "sortf" i gave you,to do this go into the terminal
type `cd (path to where you saved this download)`this will put you in the correct directory,

step 2)copy and paste.

then open up the original "sortf" file by typing `nano sortf` into the terminal.
now,copy the code in My file,the go back to `/usr/local/bin` by typing `cd /usr/local/bin` into the terminal.
then,the type `nano sortf` to open up your own file,then Copy and Paste the code you got from My file.
then press "Ctrl O" to write the stuff into that file,then press "Ctrl X" to exit the file 
(please dont forget to comfrim the changes into the file)

Step 3) Make it an executable.

you can aciheve this by going into the `/usr/local/bin` by typing `cd /usr/local/bin` into the terminal,then,
type `chmod +x "sortf"` into the terminal and press Enter. Now its a Executable and yoru good to go!
just Reboot linux and tahts it with the intallation.

Step 4) How to use?


`sudo listf` is out key command,now its out first Prefix time"


type "sudo listf -i" , `i` for "file" and


type "sudo listf -f" , `-f` for "folder"
 
 after that...
 
its time for our next set of prefixes!


type "sudo listf (first set of prefixes) -k" , `-k` to see the file size in kilobytes.


type "sudo listf (first set of prefixes) -m" , `-m` to see the file size in Megabytes.

 
type "sudo listf (first set of prefixes) -g" , `-g` to see the file size in Gigabytes.

to finish off the command,just add the directory.

type "sudo listf (first set of Prefixes) (second set of prefixes) (thedirectory you want to scan)

example! "sudo listf -f -m /Home"

i hope you understand it now

if you dont, here is a simple version?

sudo listf (-i/-f) (-k/-m/-g)  (/...)







