02-24-02/26

**[Last week]**

* [Dolphin 512]
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Experimenting on settings cache + async storage, faster but have potential risk
    * [Working] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Cold launching Calendar app spends a longer time
        - Help on calendar app profiling with Danny
    * [Pending] [Bug 1117450] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on displaying callscreen is much longer after the dial button clicked

* [Stingray]
    * [Done] Create repo for tv's web component and use bower to manage them
    * [Working] Discuss how to enable test on tpbl and how to merge tv_apps

* [Study]
    * [Working] System window management

**[This week]**

* [Dolphin 512]
    * [Working] [Bug 1115304] - [FFOS7715 v2.1][AudioChannel]we can not change to speaker quickly when we hang up a call

* [Stingray]
    * [Working] Discuss how to enable test on tpbl and how to merge tv_apps

* [Study]
    * [Working] System window management

02/16-02/17

**[Last week]**

* [Dolphin 512]
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Experimenting on settings cache + async storage, faster but have potential risk
    * [Pending] [Bug 1117450] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on displaying callscreen is much longer after the dial button clicked
    * [Pending] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Cold launching Calendar app spends a longer time
        - Help on calendar app profiling with Danny

02/09-02/13

**[Last week]**

* [Dolphin 512]
    * [Working] [Bug 1117450] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on displaying callscreen is much longer after the dial button clicked
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Provide wip to save system app boot up time
    * [Working] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Cold launching Calendar app spends a longer time
        - Help on calendar app profiling with Danny
    * [Done] [Bug 1091483] Unable to show stk dialog (e.g. user confirmation dialog) when foreground app is Callscreen
        - Answer partner question about z-index for stk dialog and call screen

* [Stingray]
    * [Done] [Bug 1131447] - [Stingray][demo] apply visual to fling receiver
    * [Done] [Bug 1132775] - [Stingray] Fix localizeElement in tv shared utils

02/02-02/06

**[Last week]**

* [Woodduck]
    * [Done] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Land on master, uplift to 2.1/2.2

* [Dolphin 512]
    * [Working] [Bug 1117450] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on displaying callscreen is much longer after the dial button clicked
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Provide wip to save system app boot up time
    * [Invalid] [Bug 1121805] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on hiding callscreen after hangup is much longer
        - By design, should be invalid

**[This week]**

* [Dolphin 512]
    * [Working] [Bug 1117450] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on displaying callscreen is much longer after the dial button clicked
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Provide wip to save system app boot up time
    * [Working] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Cold launching Calendar app spends a longer time
        - Help on calendar app profiling with Danny

01/26-01/30

**[Last week]**

* [Woodduck]
    * [Done] [Bug 1127218] - [FFOS2.0][Woodduck][screen reader]Hope to disable screen reader
        - Answer partner questions
* [Dolphin 512]
    * [Done] [Bug 1094632] - [Woodduck][Email]No attachment icon in the right of the email which has attahments in local draft folder
        - Land on master, uplift to 2.1/2.2
    * [Done] [Bug 1112971] - Can't remove cell broadcast notification from utility tray
        - Uplift to 2.1
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Provide wip patch and add some log to invstigate
    * [Pendind] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Got r+, QA verify and approval pending
    * [Pending] [Bug 1117469] - [SMS][dolphin][FFOS7715 v2.1][performance] The time took for cood booting of sms app is much longer
    * [Pending] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Open a background calendar app spend a longer time
    * [Wontfix] [Bug 1119735] - [FFOS7715 v2.1]Need to added the apns in 'ril.data.cp.apns' into the settings apnlist
* [Study]
    * [Pending] System window management

**[This week]**

* [Dolphin 512]
    * [Working] [Bug 1117445] - [FFOS7715 v2.1][performance] it is slow to start up by normal boot-strap or restart in FFOS2.1
        - Provide wip patch and add some log to invstigate
    * [Working] [Bug 1117450] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on displaying callscreen is much longer after the dial button clicked
        - Start profiling
    * [Pending] [Bug 1121805] - [Dialer][dolphin][FFOS7715 v2.1] [performance] The time spent on hiding callscreen after hangup is much longer
    * [Pending] [Bug 1117469] - [SMS][dolphin][FFOS7715 v2.1][performance] The time took for cood booting of sms app is much longer
    * [Pending] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Open a background calendar app spend a longer time

01/19-01/23

**[Last week]**

* [Woodduck]
    * [Done] [Bug 1119696] - [FFOS2.0][Woodduck][Voicemail]MS go to another SIM when set the voicemail number
    * [Done] [Bug 1096868] - [Notifications]The screenshot can't be opened successfully on notifications bar after restarting device
    * [Wontfix] [Bug 1116671] - [FFOS2.0][Woodduck][SMS]launch Messaging from contact won't change message unread status
* [Dolphin 512]
    * [Done] [Bug 1062558] - Find my Device app launches when unlocking the device, even when FMD is disabled
    * [Working] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Discuss w/ Arthur and made another patch, review pending
    * [Done] [Bug 1115322] - [FFOS7715 v2.1] [Clock] Alarm which is repeat everyday cannot work after changing system time to an earlier one
        - Providing workaround patch for partner
* [Stingray]
    * [Done] [Bug 1123173] - [Stingray] jshint failure in tv browser
    * [Done] [Bug 1123174] - [Stingray] jshint failure in tv dlna-player
    * [Done] [Bug 1123175] - [Stingray] jshint failure in tv smart-home
    * [Done] [Bug 1123176] - [Stingray] jshint failure in tv smart-settings
    * [Done] [Bug 1123191] - [Stingray] jshint failure in tv build script
    * [Done] [Bug 1123192] - [Stingray] jshint failure in tv shared
    * [Done] [Bug 1123184] - [Stingray] Enable l10n args format in browser context menu
    * [Done] [Bug 1123569] - [Stingray][Demo] Lock orientation for all apps
* [Study]
    * [Pending] System window management

**[This week]**

* [Dolphin 512]
    * [Working] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Discuss w/ Arthur and refine patch
    * [Working] [Bug 1094632] - [Woodduck][Email]No attachment icon in the right of the email which has attahments in local draft folder
    * [Pending] [Bug 1119735] - [FFOS7715 v2.1]Need to added the apns in 'ril.data.cp.apns' into the settings apnlist
    * [Pending] [Bug 1117469] - [SMS][dolphin][FFOS7715 v2.1][performance] The time took for cood booting of sms app is much longer
    * [Pending] [Bug 1117465] - [Calendar][FFOS7715 v2.1][performance] Open a background calendar app spend a longer time
* [Study]
    * [Pending] System window management

01/12-01/16

**[Last week]**

* [Woodduck]
    * [Pending] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Review pending
    * [Pending] [Bug 1062558] - Find my Device app launches when unlocking the device, even when FMD is disabled
        - Review pending
    * [Pending] [Bug 1116671] - [FFOS2.0][Woodduck][SMS]launch Messaging from contact won't change message unread status
        - Wait for Bug 1105548 fix on master and pick up to 2.0m
* [Dolphin 512]
    * [Invalid] [Bug 1116696] - [Bluetooth][FFOS7715 v2.1] Bluetooth phone to switch the call option to the mobile phone handset,plug in cable headset after,the voice of the call change from the phone handset to the bluetooth headset.
    * [Working] [Bug 1115322] - [FFOS7715 v2.1] [Clock] Alarm which is repeat everyday cannot work after changing system time to an earlier one
        - Providing workaround patch for partner
* [Stingray]
    * [Done] [Bug 1120355] - [Stingray] enable jshint for tv_apps folder
    * [Done] [Bug 1120281] - [Stingray] net error is unable to load anything while GAIA_OPTIMIZE !== 1
* [Study]
    * System window management
    * How to open app from system message
        - https://cacoo.com/diagrams/GtyCwURVaVtWLHqa

**[This week]**

* [Woodduck]
    * [Pending] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Review pending
    * [Pending] [Bug 1062558] - Find my Device app launches when unlocking the device, even when FMD is disabled
        - Review pending
    * [Pending] [Bug 1116671] - [FFOS2.0][Woodduck][SMS]launch Messaging from contact won't change message unread status
        - Wait for Bug 1105548 fix on master and pick up to 2.0m
* [Dolphin 512]
    * [Working] [Bug 1115322] - [FFOS7715 v2.1] [Clock] Alarm which is repeat everyday cannot work after changing system time to an earlier one
        - Providing workaround patch for partner
* [Stingray]
    * [Working] [Bug 1123173] - [Stingray] jshint failure in tv browser
    * [Working] [Bug 1123174] - [Stingray] jshint failure in tv dlna-player
    * [Working] [Bug 1123175] - [Stingray] jshint failure in tv smart-home
    * [Working] [Bug 1123176] - [Stingray] jshint failure in tv smart-settings
    * [Working] [Bug 1123191] - [Stingray] jshint failure in tv build script
    * [Working] [Bug 1123192] - [Stingray] jshint failure in tv shared
* [Study]
    * System window management
    * How to open app from system message
        - https://cacoo.com/diagrams/GtyCwURVaVtWLHqa

01/05-01/09

**[Last week]**

* [Woodduck]
    * [Done] [Bug 1105669] - [Wifi]The wifi can't be turned off
    * [Done] [Bug 1112971] - Can't remove cell broadcast notification from utility tray
    * [Working] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
    * [Working] [Bug 1116671] - [FFOS2.0][Woodduck][SMS]launch Messaging from contact won't change message unread status
    * [Working] [Bug 1062558] - Find my Device app launches when unlocking the device, even when FMD is disabled
* [Study]
    * System window management

**[This week]**

* [Woodduck]
    * [Working] [Bug 1115493] - [FOS7715 v2.1]Setup call-forwarding for both SIM cards in DSDS, then removal one sim card and reopen the device, the status bar still shows two icons of call forwarding
        - Review pending
    * [Working] [Bug 1116671] - [FFOS2.0][Woodduck][SMS]launch Messaging from contact won't change message unread status
        - Duplicate, prepare pr for 2.0m
    * [Working] [Bug 1062558] - Find my Device app launches when unlocking the device, even when FMD is disabled
        - Prepare pr for 2.0m
* [Stingray]
    * [Working] [Bug 1120355] - [Stingray] enable jshint for tv_apps folder
* [Study]
    * System window management
    * How to open app from system message
