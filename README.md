# Toggle Hidden Files OS X Service

This is a [Service](http://en.wikipedia.org/wiki/Services_menu) to toggle hidden file display in in OS X's Finder.
i.e. if you have hidden files turned on this'll turn the off and vice versa. 

## Installation

Download the Service and open it. OS X will ask whether you want to install it to your `~/Library/Services` folder or open it in Automator. 
When installed correctly you'll see a "Toggle Hidden Files" item in the Services System Preferences pane.

## Usage

From the Services Menu select "Toggle Hidden Files". This will toggle the current Finder preference and restart Finder. Finder should restart with your previous session/windows intact.

Suggested Keyboard shortcut: `⇧ ⌘ .`, this can be set in System Preferences > Keyboard > Keyboard Shortcuts > Services > General. This remians compatible with the modal dialogue keyboard shortcut, and extends it to Finder wide. 

Further information on keyboard shortcuts at [Apple's KB](http://support.apple.com/kb/PH3957) or 