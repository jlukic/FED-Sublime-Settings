# FED-Sublime-Settings

## What You Get

### Default Settings

* 2 Space Tabs
* UNIX File Endings
* Remove extra whitespace on save
* Sort CSS rules on save
* [Phoenix Theme](https://github.com/netatoo/phoenix-theme)
* [Monokai Soda Colors](https://github.com/buymeasoda/soda-theme/)
* Additional themes and colors available (see below)
* Code highlighting for LESS/Coffeescript
* Inline javascript and CSS linting
* Additional features (see package list)

### Added Shorcuts 

* ``Ctrl + U`` - Uppercase current selection
* ``Ctrl + I`` - Reindent entire file
* ``Ctrl + T`` - New file/tab
* ``Ctrl + Space`` - Delete trailing spaces
* ``Ctrl + Left`` - Change to left column and resize
* ``Ctrl + Right`` - Change to right column and resize
* ``Ctrl + (Cmd / Alt) + Right`` - Goto next html/css rule matching highlighted html/css
* ``Ctrl + (Cmd / Alt) + Left`` - Go to previous html/css rule matching highlighted html/css
* ``Ctrl + (Cmd / Alt) + A`` - Align currently selected variables
* ``Ctrl + (Cmd / Alt) + C`` - Sort selected CSS rule
* ``Ctrl + (Cmd / Alt) + ?`` - Search Stack Overflow
* ``Ctrl + (Cmd / Alt) + p`` - Open FTP browser
* ``Ctrl + (Cmd / Alt) + W`` - Close idle tabs

### Useful Default Shortcuts

* ``Ctrl + /`` - Change line to comment
* ``Ctrl + D`` - Select next instance of text
* ``(Cmd / Alt) + F3`` - Select all instances of text
* ``Ctrl+ p`` - Search project
* ``Ctrl+ r`` - Search for definition in current file
* ``Ctrl+ shift + p`` Execute command
* ``Ctrl + shift + f`` Find all

##Installing

#### 1. Install Packages

Copy this repo's content to 

#####Windows
  
    C:\Users\YOURNAME\AppData\Roaming\Sublime Text 2\Packages

#####Mac

    /Users/{user}/Library/Application Support/Sublime Text 2/Packages

#### 2. Install dependencies

* If you would like to use git commands [install git](http://git-scm.com/book/en/Getting-Started-Installing-Git)
* If you want to use jshint linting [install node and npm](http://nodejs.org/download/) then [install jshint](http://jshint.com/install/). **Make sure your node path is correct in SublimeLint settings**

#### 3. Setup JSHint and CSSLint Settings (Optional)

After setting up Sublime Lint you may want to modify the strictness of the linting. 

To do this open ``Preferences -> Package Settings -> SublimeLint --> Settings - User`` and look for the object specifying linting settings. For more information on setting this up check out the documentation for [JSHint settings](http://www.jshint.com/docs/config/) and [CSSLint Settings](https://github.com/stubbornella/csslint/wiki/Rules)

#### 4. Setup FTP Sync (Optional)

If you would like to have your files sync on save, hit ``ctrl+option+shift+p`` or ``ctrl+alt+shift+p`` and use the menu to add a new ftp server.

Then in the root of your project file add a ``sftp-config.json`` file. [More information](http://wbond.net/sublime_packages/sftp/settings)

#### 5. Modify CSS Sort Order (Optional)

By default CSS rules are ordered from outside in (Display, Margin, Box, Background, Font, Vendor) using a custom rule set. 

To change the CSS sort order modify the order listed in  ``Preferences -> Package Settings -> CSSCOmb --> Sort Order - User``


## Packages

**Themes**

* **[Phoenix](https://github.com/netatoo/phoenix-theme)**: Complete Sublime Text theme
* **[Zenburn](https://github.com/colinta/zenburn)**: Code highlighting theme
* **[Tomorrow](https://github.com/chriskempson/tomorrow-theme)**: Code highlighting theme
* **[Soda](https://github.com/buymeasoda/soda-theme/)**: Code highlighting theme

**General**

* **[Git](https://github.com/bgreenlee/sublime-github)**: Adds shortcuts for git commands from command prompt
* **[Package Control](https://sublime.wbond.net/)**: Install and remove sublime text packages
* **[Tidy Tabs](https://github.com/bradleyboy/TidyTabs-Sublime)**: Shortcuts to close tabs that have not been open recently
* **[Alignment](http://wbond.net/sublime_packages/alignment)**: Aligns variables on colons or =
* **[Function Name Display](https://github.com/akrabat/SublimeFunctionNameDisplay)**: Shows current function name in status bar
* **[SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel)**: Intelligent autocomplete based on your codebase
* **[Split Screen Resizer](https://github.com/iamjessu/sublime-SplitScreen-Resizer)**: Shortcuts to change between tabs and resize to ratio of screen
* **[Toggle Quotes](https://github.com/spadgos/sublime-ToggleQuotes)**: Toggle between single and double quotes more easily
* **[SFTP](http://wbond.net/sublime_packages/sftp)**: (Trial) Allows (S)FTP sync on save
* **[Search Stackoverflow](https://github.com/ericmartel/Sublime-Text-2-Stackoverflow-Plugin)**: Shortcut to search stackoverflow directly from sublime

**Javascript**

* **[SublimeLinter](https://github.com/SublimeLinter/SublimeLinter)**: Alerts to javascript errors on save
* **[Coffee Formatter](https://github.com/derekchiang/Sublime-CoffeeScript-Formatter)**: Code highlighting for Coffeescript

**CSS & HTML**

* **[LESS](https://github.com/danro/LESS-sublime)**: Code highlighting for LESS CSS
* **[Goto CSS Declaration](https://github.com/rmaksim/Sublime-Text-2-Goto-CSS-Declaration)**: Automatically move to CSS definition from highlighted html
* **[CSSComb](https://github.com/csscomb/CSScomb-for-Sublime)**: Formats rules in specified order
* **[Prefixr](http://wbond.net/sublime_packages/prefixr)**: Adds vendor prefixes to current css rule
