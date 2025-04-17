# Hackintosh-Chime-Boot-Sound

Hackintosh Chime Boot Sound
nicoswd-Carillon

Carillon is an open source OS X app, specifically for Hackintosh machines, that plays the classic "Chime" boot sound on startup that real Macs have.

A new launch daemon will be added that triggers the sound, meaning, unlike most similar apps, this one runs much earlier during the boot process, even before the login screen appears. No crappy AppleScript solution that triggers when you're already on the Desktop, no outdated PrefPane

INSTALL 
/usr/local/bin/Carillon 
/System/Library/LaunchDaemons/com.nicoswd.Carillon.plist

sudo chown root:wheel /usr/local/bin/Carillon 
sudo chown root:wheel /Library/LaunchDaemons/com.nicoswd.Carillon.plist

UNINSTALL To uninstall Carillon, remove the following files from your system:
 
/usr/local/bin/Carillon 
/System/Library/LaunchDaemons/com.nicoswd.Carillon.plist

VIEW HIDDEN MAC FILES

defaults write com.apple.Finder AppleShowAllFiles true killall Finder

defaults write com.apple.Finder AppleShowAllFiles false killall Finder








