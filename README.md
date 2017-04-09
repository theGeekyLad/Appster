# Appster
For the kind who're fanboys of custom ROMs, I'd agree that tastes change quite often as the market gets you more! Many of us (like me) don't have a stand by phone on which we'd have all our custom ROMs testing and swapping done and that's exactly when the question of data and apps backup and restore comes into the play. Yet, data stays back when you swap between ROMs but all those plethora of apps would bid adieu and restoring them one-by-one on your new ROM makes it cumbersome, especially if you've got like more than 25~30 apps!

HIGHLIGHTS
So to deal with all those problems, I've built a mini tool that runs on Java and it restores your apps from the backup folder all by itself. You needn't accept the installation or do anything at all! Just leave your device plugged in with debugging on and hit the install button within Appster and in about 6~7 minutes (for a folder of 20 apps) you'd have all of them up on your phone and running!

There are quite a few of them on Play Store too that do all this stuff in situ on your phone itself but most of them require root and get quite cumbersome (especially say if you clear it off recent apps or Android decides to re-prio its background apps). This program doesn't require no root access or anything of that sort.

Got a new phone? Sit back and let this guy restore all your apps from your backup folder onto your new phone!

PREREQUISITES
- JDK for Windows - which if you don't have, you can't run any Java based applications on Windows. Grab it from here just in case you don't have it.
- A folder named apps containing all the apps you want to restore
- An Android device (for real!) with USB Debugging enabled in Settings
- Some coffee to chill for about a few minutes (you could even YouTube - well, suit yourself )

PROCEDURE
- Make sure Appster.jar as well as the folder named apps is placed inside the same folder
- Dump all your apps into the folder apps regardless of the names - just make sure the .APK extension is preserved
- That's done! Now just plug your device in and make USB Debugging is enabled
- Start Appster.jar
- Now tap Install and let it play. Just sit back, relax and let Appster take care of the rest!

BUGS
May the bugs be damned! Well, it works slick with no bugs unless you've not got Java on your system or there's a faulty install of Java. If that's the case, before Appster even launches, it throws an error saying "exception has occurred". The same happened on my buddy's PC recently because of a faulty configuration of Java.

Nevertheless this is quite a new project so there may be a few bugs which you could notify! Would consider open sourcing it quite soon after which the source code would be up here.

NOTES
- You won't be allowed to close this program while it's executing (unless and until you're quite smart and fall back to the Task Manager )
- Appster may take quite some time depending on the number and size of your apps
- Do not disconnect your device while it's in progress
- You can use your phone normally (calls, messages, etc.) in the meanwhile

Well! That's most of it. Let me know if this program works perfect for you and at the same time, do let me know of any bugs in the Issues section. If the same error that says "an exception has occurred" shows up, put it down in the Issues section and I'd look into it in detail.

Cheers and thanks for reading this post! 
