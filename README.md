# SublimeConf

1. Need to [install package control](https://packagecontrol.io/installation) first of all
2. Close sublime
3. (On windows) go to: `C:\Users\<YOUR USERNAME>\AppData\Roaming\Sublime Text 3\Packages\User`
4. `git init`
5. `git remote add origin http://github.com/samedii/SublimeConf`
6. `git fetch`
7. `git reset origin/master --hard`
8. Open sublime and it will install the packages

If you see an error about a theme in step 8, then remove this line: `"color_scheme": "Packages/User/SublimeLinter/Monokai (SL).tmTheme",` from Preferences.sublime-settings