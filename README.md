Instructions for installation:

Download and unzip the files
Open the terminal and type sudo cp (drag the first file into the terminal) "/Library/Scripts/Folder Action Scripts/" 
Press enter
Enter your password and press enter
Open the terminal and type sudo cp (drag the second file into the terminal) "/Library/Scripts/Folder Action Scripts/"
Press enter

Right click or hold control and click on the folder that you want to assign these scripts to
Select "Folder Actions Setup..."
A dialog box will appear.  Press "Run"
Make sure "Enable Folder Actions" is checked
Click the + box and add the first script.
Click the + box and add the second script.

A permissions notification will pop up. Press "Ok"

Note- when using with Dropbox folders, the dropbox folders need to be set to "Available offline"
Other Note- make sure that Music/iTunes is not copying files into the media library under Settings->Files-> uncheck
the box that says "Copy files to Music Media folder when adding to library"

In order to use the logging version-
move dropboxautologger.sh to your desktop
in the terminal type "sudo chmod +x" and then drag the file from your desktop into the terminal. press enter. it will prompt you for your password. type it in and press enter. 
This makes the script executable.
The logs will be saved to a file in your home folder called "dropbox_automation.log." You can view them in the console or any text editor.

To use the CreatePlaylist_AddFiles utility, open the script in Script Editor and press the little hammer to compile. Then press the play button.
It will promp you with a directory that you wish to add. It was designed specifically for Dropbox/WGXCStudioAudio/Active/ - so in other words, select every folder you wish to add in the active directory either by using the shift or command keys and then press open. 

It will create a playlist for each folder that you select and it will add all contents of that folder to it's corresponding playlist. 

This is useful for new computer setups.
