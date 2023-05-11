# Windows-and-Linux-KeyLogger
A very simple and easy way to use the windows and linux keylogger 

# LINUX 
# installation
The following instructions will install Keylogger using pip3 .
  pip3 install -r requirements.txt
# or
  pip3 install pyxhook
  
 # How to run it
 It will begin logging your keystrokes when you run the command nohup python3 keylogger.py: 'No hangup' is the definition of the word nohup. Nohup does not return to the shell command prompt after running a command in the background when used with the '&' character.
 
 
 **$~/Keylogger/linux$ nohup python3 keylogger.py &
[1] 12529 //this is the keylogger's PID (process ID)
$:~/Keylogger/linux$ fg**

The Keylogger is now running! It will log your strokes to a file . Stop it by typing the command fg then hitting CTRL+C

or

kill {PID} for example kill 12529

# uses
Some uses of a keylogger are:

    Business Administration: Monitor what employees are doing.
    School/Institutions: Track keystrokes and log banned words in a file.
    Personal Control and File Backup: Make sure no one is using your computer when you are away.
    Parental Control: Track what your children are doing.
    Self analysis
