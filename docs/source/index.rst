Welcome to Zhongli's documentation!
===================================
✨ New to Zhongli Robot?
🤖 Here is a Basic Zhongli Configuration Checklist:

🦠 First and foremost use /sanitize to clean yourself before you proceed.

**Enable welcome security, soft or strong.:**
/welcomemute strong
Note: Tries to limit what a user can do when they newly join a group
Strong = Give them 120 seconds to press button, if they fail, kick them off the group
Soft = Restricts them to text only for 24hours after joining

**Protect accidental contact leakage**
/lock contact

Stop letting users add bots (Ideally, disable the "Add Users" permission in group settings)
/lock bots

**Private group? Worried about invite links?**
/disable invitelink
 
**Lock forwarding stuff into the group**
/lock forward

**Private group? Avoid users kicking themselves by mistake**
/disable punchme

**Users/Spammers flooding non-stop? (Adjust the number to your needs)**
/setflood 7
*Set what to do when flood control happens using*
/setfloodmode mute/ban/tmute
Example: /setfloodmode tmute 15m
 
**Don't want some Zhongli commands enabled in group?**
/listcmds and then use /disable namehere
/listmodules and /disablemodule namehere
Note: if this conflicts with any other bot in group then use /disable@SaitamaRobot to send that message only to Saitama.

**Want to auto warn users when they say specific stuff?**
See warns > /addwarn command help

**Don't like some words to be spoken in group? Blacklist them using**
/addblacklist word1
word2
"entire sentence here"
Note: You can use "quotes for" if there is a sentence and not a word. 

**Don't want to explain to each newbie? Setup rules!**
/setrules
 Awesome Rules here

**Don't want our awesome random welcome messages? Use a custom one using :**
/setwelcome Hi, welcome to my group
Note: This command has more stuff you can use, see /welcomehelp first.

**Have multiple groups to handle? Setup Federations!**
Read help for this, this has a bit of a learning curve.

**Enable reporting so that your users can report troublemakers to admins.**
/reports on
Note: Send in group to enable group reports and send in Saitama's pm so that he will report any enabled group to Your pm.

**Want to track which of your admins did what? Who banned who? Who joined?**
Setup a log channel, see help for instructions.


**Lastly, most of these would apply to almost any Zhongli like bot, please do spread the word around for basic chat control and protect yourself from spammers/scammers and troublemakers.**

Need help? Come visit us at @manhwarecommend
