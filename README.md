# Wordle

<img width="697" alt="Screen Shot 2022-01-31 at 7 36 46 PM" src="https://user-images.githubusercontent.com/64491468/151895732-61e8fbdc-728a-4403-93b0-267bea2ece79.png">


My copycat version of the hit game Wordle (created by Josh Wardle). Written using python and the PyGame library to produce visuals. 

To download, open terminal and enter:

git clone https://github.com/hillspen/wordle.git

This will clone the code repo and create a local copy on your machine. Navigate to the directory it is stored in and you can run the python script (Wordle.py) from there. Dependencies: pygame (install using **pip install pygame**)

Alternatively, if you want to run it without having to invoke python every time you can create a standalone desktop application by entering terminal, navigating to the directory where the code is stored (alternatively you can modify the file names to the full filepath if you are having issues), and running (these commands are for Mac, you can use the script to create an .exe file for Windows):

pip install py2app

py2applet --make-setup Wordle.py words.txt guessingWords.txt WordsWithFriends_w_letter_key_7013.ico

python setup.py py2app -A


This will create an application called Wordle in your directory that can be moved to your applications folder and run independently. 

Future updates will likely include long-term score tracking and possibly sharing functionality.
