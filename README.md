# CatchMouse
Move the cursor between multiple displays using a shortcut. (Version 1.2)

[CatchMouse Repo](https://github.com/round/CatchMouse)

[CatchMouse v1.0](https://web.archive.org/web/20150502123813/http://ftnew.com:80/catchmouse.html)

[CatchMouse v1.2](https://github.com/microsoft/PowerToys/files/5012390/CatchMouse2.zip)

## usage
1. unzip `CatchMouse.zip` and move `CatchMouse.app` into `/Applications` path
```
mv ~/Desktop/CatchMouse.app/ /Applications/CatchMouse.app/
```
1. set up permission
    1. Open the Apple menu, and click System Preferences.
    1. Click Security & Privacy.
    1. Click the General tab.
    1. Click the lock in the lower right corner of the window.
    1. Enter your username and password when prompted, and click Unlock.
    1. Click the App Store and Identified Developers radial button.
    1. Look for “(App Name) was blocked from opening because it is not from an identified developer” and click Open Anyway. (In older versions of macOS, you could click Anywhere and then click Allow From Anywhere.)
    1. Try rerunning the app.
1. hide app icon from dock
edit the file `/Applications/CatchMouse.app/Contents/Info.plist` with adding following code before `</dict>`. then restart CatchMouse
```
<key>NSBGOnly</key>
<string>1</string>
```
