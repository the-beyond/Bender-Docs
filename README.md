# Bender Documentation
This is intended as a publicly available documentation for WMD's Bender Discord Bot. 
The bot has been developed by feather4102 in Python using the Nextcord module which is a fork of the original discord.py module.  

There are lots of easter eggs to find!

* The Prefixes for Bender bot are ```$```, ```?``` and ```? ```. For my examples I will always use \$, but it is interchangable with the others if you wish, and there are multiple so people can decide what they like. A large amount of commands however are slash commands only. 

### Key Notes
* Anything listed in \<> is a required argument for the commands and the command will not work without it, __DO NOT INCLUDE THE \<> IN THE COMMAND__.
* Anything listed in \[] is an optional argument for the commands and allows the command to use what you add, __DO NOT INCLUDE THE \[] IN THE COMMAND__.
* For slash commands I have included what each item in <> or [] represents by writing it in as ```<title: purpose>``` with the purpose being everything after the colon. 


## Utility Commands 
* ```$ping``` - Get the bot's ping!
* ```/ping``` - Get the bot's ping!
* ```/documentation``` - Get the link for the bot's documentation!
* ```/factionlink``` - Get the faction link!
* ```/stockfund``` - Get the link to the stock fund info!
* ```/feedback <feedback_type: choose the tyoe from the list> <message: the message you want to send me> [anonymous: choose to be anonymous or not]``` - Send me feedback about the bot!
* ```/ticket <issue: write the issue you are having> <message: do you want me to message you to get more info?>``` - Submit a ticket to me if something goes wrong!

## Request Commands
* ```$bank <amount>``` - Request an amount of money from the bankers!
* ```/request bank <amount: amount of money needed> [message: optional message]``` - Slash command to request money from the bankers!
* ```/request stock_deposit <amount: amount of money to deposit>  [message: optional message]``` - Request to deposit money to the stock fund!
* ```/request stock_withdrawal <amount: amount of money to withdrawal>  [message: optional message]``` - Request to withdrawal money from the stock fund!

## Announce/Log Commands 
### All of these slash commands are part of the /announce command. For a guide to embeds see the bottom of this documentation!
* ```/announce basic_embed <title: The embed title> <main_text: the main text block of the embed> [embed_color: optional color for the embed block, needs to be hexadecimal (see guide] [footer_text: optional footer text for the embed]``` - Send a basic embed message!
* ```/announce advanced_embed <embed_title: The embed title> [main_text: the optional main text block of the embed] [embed_color: optional color for the embed block, needs to be hexadecimal (see guide] [field#_name: Enter the name for this # field] [field#_value: Enter the text for this # field, keep in mind if you use a field#_name you need a field#_value] x5 [footer_text: optional footer text for the embed]``` - Send an advanced embed message!
* ```/announce leadership_embed <embed_title: The embed title> <channel: select the channel to send to> [mention: Select a role to mention!] [main_text: the optional main text block of the embed] [embed_color: optional color for the embed block, needs to be hexadecimal (see guide] [field#_name: Enter the name for this # field] [field#_value: Enter the text for this # field, keep in mind if you use a field#_name you need a field#_value] x5 [footer_text: optional footer text for the embed]``` - Send an advanced embed message to any channel! (Leadership and Council only)
* ```/announce dm <member: member to DM> <message: message to send>``` - Send a DM to a user with the bot! (Leadership and Council only)
* ```/log pastmember <name: torn name> <id: torn id> <type: Kicked or Left> <reason: Reason/Notes>``` - To log past members! (Leadership and Council Only)

## Fun Commands
* ```$rigged``` - Calls out Fatties for rigging things!
* ```$conversions``` - Get some handy conversions!
* ```$tanuki``` - See the almighty tanuki!
* ```$hnb``` or ```$bnh``` - Blackjack and hookers!
* ```$coolstorybro``` or ```$csb``` = Cool story bro!
* ```$quit``` - idk how to describe this lol 
* ```$scamming``` or ```$scam``` or ```$scammer``` - It's not blackmail!

## Fun Slash Commands
* ```/pumped mom <target: who is getting their mother pumped> [pumper: who is doing the pumping, if left blank defaults to the command user]``` - Someone is gonna pump someone else's mom. 
* * ```/pumped dad <target: who is getting their father pumped> [pumper: who is doing the pumping, if left blank defaults to the command user]``` - Someone is gonna pump someone else's dad. 
* ```/askbender <question: Needs to be a Yes or No question>``` - Ask Bender a question! (Kinda like a magic 8 ball)
* ```/attack punch <target: who to attack> [attacker: who is attacking, if left blank defaults to the command user] - Punch someone!
* ```/attack rko <target: who to attack> [attacker: who is attacking, if left blank defaults to the command user] - RKO!
* ```/attack kick <target: who to attack> [attacker: who is attacking, if left blank defaults to the command user] - Kick someone!
* ```/attack scm <target: who to attack> [attacker: who is attacking, if left blank defaults to the command user] - Give someone sweet chin music!
* ```/attack truckerbomb <target: who to attack> [attacker: who is attacking, if left blank defaults to the command user] - Throw a truckerbomb at someone!
* ```/attack superkick <target: who to attack> [attacker: who is attacking, if left blank defaults to the command user] - Superkick someone!
* ```/drugs <target: who to tell that drugs are bad>``` - Tell someone drugs are bad!
* ```/offended <offender: who offended you>``` - Make sure someone knows they offended you!

# A Quick and Dirty Guide to Embeds
## The Key Parts of an Embed - See image at the bottom for reference where each thing (except color) is labeled with (). 
* Title - This appears at the top of the embed in large letters
* Description/Main Text - Makes up the core chunk of text of the embed. 
* Color - The color is represented on the left hand side of the embed and needs to be in hexadecimal form, I like to use the [google color picker](https://www.google.com/search?q=color+picker&oq=color+picker&aqs=chrome.0.69i59j0i20i263i512j0i433i512j0i131i433i512j0i512j0i433i512l3j0i131i433i512.2226j0j9&sourceid=chrome&ie=UTF-8). You want to use thr HEX option, without the #. So in the image below it would be ```fcba03```.
![image](https://user-images.githubusercontent.com/70727679/196340449-77fc5d4b-e22f-4656-bd9b-840c82c829c8.png)
* Fields - Fields have a name and a value. The advanced embed command allows for up to 5 fields total, keep in mind if you us a field name, that name needs to have a value as well. And you can't have a value without a name. So for example if you write in something for field1_name you also need to write something for field1_value. 
* Footer - The tiny text at the bottom of the embed message
![image](https://user-images.githubusercontent.com/70727679/196341467-434dff5f-36b5-4b9c-ae12-4b1b3b26651f.png)

