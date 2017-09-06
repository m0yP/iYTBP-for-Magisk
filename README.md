# iYTBP for Magisk v3.0

This module works only in Magisk 13.3 and 14.0. Template has been rewritten so there's no backwards compatibility.

Previous version was based on vemacs' [Adfree YouTube Template](https://forum.xda-developers.com/apps/magisk/module-adfree-youtube-template-t3532753) and Master_T's [iYTBP](https://forum.xda-developers.com/android/apps-games/app-iytbp-injected-youtube-background-t3560900).

Props go out for ZaneZam, Razerman and laura almeida from XDA for their new [Vanced](https://forum.xda-developers.com/android/apps-games/app-iytbp-injected-youtube-background-t3560900) version which is the new YouTube mod this module is based on.

Its main purpose is to have an ad-free and background playback, as we had with the the Xposed's module [YouTube Background Play](http://repo.xposed.info/module/com.pyler.youtubebackgroundplayback).

Inside system/app/YouTube there's a "lib" folder with another named "Architecture" inside. This is, as name suggests, the library folder that contains extra features for YT, i.e. support for 360º videos. To use it properly, you need to rename the folder to "arm", "arm64", "x86" or "x86_64" and place inside the contents of the "lib" folder for the original YT apk.

It has been tested in AOSP/Lineage based ROMs, Motorola and Samsung's stock ROMs. Just flash it within Magisk Manager or TWRP.

For downloads please visit the [XDA thread](https://forum.xda-developers.com/apps/magisk/module-iytbp-magisk-t3619705)

All credit goes to the original developers, I just put stuff together.
