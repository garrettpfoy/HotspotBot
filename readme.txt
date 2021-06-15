Process:

Information needed (inputs):
Asset Number

Information available (assuming inputs):
SSID (Wifi name)
Password
Device ID
Student MAC Address
Student ID


Process Steps:
Navigate to 192.168.0.1 → Done
Login
Password Likely: 5gT8at4x → Done (main.py) (combined)
Password Unlikely: admin → Done (admin.py) (combined)
Assure profile is TMobile US (http://192.168.0.1/#/NetworkSettings)  → DONE
Setup Firewall Whitelist (http://192.168.0.1/#/NetworkSettings) → Done
Add admin MAC addresses
MAC: d4:d2:52:55:2f:a8 NICKNAME: A000031388 → Done
MAC: 48:89:e7:03:34:b9 NICKNAME: A000060098 → Done
Add student MAC address
Gather MAC from roster → Done
MAC: ^^^ NICKNAME: Asset Number (input) → Done
Ensure password and name matches password sheet → Done


Installation:
Download Python from https://www.python.org/downloads/ (Stable Version: 3.8.5)
Run Python Executable
Uncheck “Install for all users”, and check “Add Python to PATH”
Click install
Once python is installed, open an admin command panel. To do this
Open your search bar (bottom left)
Type in “Command Prompt”
RIGHT-CLICK the icon and click “Run as Administrator”
Install python packages using PIP (included with Python 3)
In command prompt type:
“pip install gspread”
“pip install playsound”
“pip install selenium”
Download program from google drive
Navigate to: GOOGLE DRIVE LINK
Right click “Hotspot Automation” at the top in the path
Click Download
Setup root directory
Find your downloaded folder and drag it to wherever you want.
In your chosen location, open the zipped download and extract it’s contents
Once you are done, delete the zipped folder.
Run the script
Open Command Prompt (Search bar → Command Prompt → Run as Administrator)
Navigate to your chosen directory
Find where you extracted the folder, and enter the “src” folder.
At the top of your view, you should see a path, click it to revel the text-based folder path, it should look something like this:

Copy that text, and right-click the file “main.py”
Click “Open With” and select Notepad
In the notepad, find the line “ROOT_DIRECTORY = “”  “
Paste the file path into those quotation marks
Save the file
Once completed go back to your Command Prompt and navigate to your src directory
Type “cd “[FilePath]”
If there is a space anywhere in the path, you must use quotes
You should see the file update in your command line
Once you are in your root directory, run the start command
For a normal password (not admin), use “python main.py”
For an abnormal password (admin), use “python admin.py”
