# inj-tichu-card-log
Injected Card Logger for onlinetichu.com

You will need an injection plugin!

Set the website zoom to 80% for best visual results!

# SETUP:
> Download a code injector plugin that supports html, css and js!
> open code.html in this repository
> Copy all the plain HTML code (not the <style> or the <script>) and paste into where you can inject your HTML
> Copy all the <style> contents and paste it in your CSS inject
> Copy all the <script> contents and paste it in your JS inject.
> Enable the code injection for only this website.

If you've done everything right, from now on when you join the website you'll see a red button ("Inject UI Toggle") on the bottom left
That button hides and shows the injected card logger. For minimum interference with the rest of the website, it's recommended to only 
have the UI toggled on when you're on a table.

In the injected UI, you can see a "Messages will be displayed here" line. This is where the logger will notify you for events triggered (like
logging starting, stoping or the log being reset)

Below that, there are 3 red buttons.
"Start logging!" will start the card logger, Every card that is played will now be observed and logged by the script.
"Stop logging!" stops the above process. It can be restarted again by clicking on the start button.
"Reset log!" will reset the card log (located below).

Finally, below the 3 buttons, you will find a list of all the tichu cards in the game, including the 4 special ones.
whenever a card is played, it will disappear from the list until the log is reset. You can also click on cards to hide them from the log.

_Hiding the UI doesn't reset the log, nor does it stop the logging process.

# *NOTE:
  The fact that dogs dont disappear from the log when played is a known issue that I will have fixed very soon.
  I will also add an auto-reset function, so that when a round ends and players get their new cards, the card log will be automatically reset so that the user
  doesnt have to reset it manually after every round.*
  
