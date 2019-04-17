# Move-Safari-Tabs-to-Chrome
Applescript Quick Action that will move all of your open Safari tabs to a Google Chrome window. Pressing a hotkey that you assign to this service will move all of your open tabs in Safari to Google Chrome, closing them as it goes. Once all of the tabs have been moved to Chrome, it will quit out of Safari. If Safari is not open, the script will do nothing.


*If you're not familiar with using Automator or creating Applescripts, follow the instructions below to set up this service.*
**To set this up as a hotkey in Safari, follow these instructions:**
1. Open the "Automator" application on your Mac.
2. Leave the type as "All" and create a new document in your desired folder. I save mine in the Automator iCloud Drive.
3. Under "Choose a type for your document", select "Quick Action" and click "Choose".
4. In the right window,  leave the "Workflow recieves" input as "Automatic (Nothing)" and change the application to "Safari". If you want to change the image or color that corresponds to this service you can do that here too. 
5. In the Actions library on the left, scroll down and find "Run AppleScript" and double-click it or drag it over to your workspace.
6. Delete all of the default script in the "Run AppleScript" text box and replace it with the script I provide in "MoveSafariTabsToChrome.txt".
7. Save the service (CMD+s).
8. Open the System Preferences application on your Mac and go to Keyboard->Shortcuts. 
9. Select "Services" in the left window and scroll all the way down to the "General" section.
10. Find the service you just made, make sure the checkbox next to it is selected, and click "Add Shortcut". Then press down your desired keys that will serve as your hotkey (I used CMD+SHIFT+z).

After following these steps, whenever you have numerous tabs open in Safari you can press your hotkey and it should open all of those tabs in Chrome and close them all in Safari. 

___
Credit to user [robmathers](https://apple.stackexchange.com/users/10167/robmathers) for providing the code that got me started and to user [markhunte](https://stackoverflow.com/users/261305/markhunte) for providing the code that allowed me to check if Safari is running before running the rest of the script.
___
Note: I have not tested how this script works when numerous Safari windows are open or numerous Chrome windows are open. I plan to do this in the future and will update this repo when I do.
