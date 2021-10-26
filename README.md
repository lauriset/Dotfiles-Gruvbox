# DragoonFox Changed to Gruvbox

A Firefox-CSS theme designed to replicate explorer tabs shown in the poplar Dragoon UI by KaLam1ty-AC, and made in the renowned DragoonX theme by niivu. A big thank you to MrOtherGuy for his helpful CSS snippets website.

Works perfectly with my (https://github.com/Blu3Jive001/DragoonX) rice.

## Setup

### Firefox css

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Create a folder and name it **`chrome`** (with lowercase).
5. Then paste the all of the files into the folder.
6. You'll need to enable Title Bar in "Customize Toolbar" (found by right clicking tab bar)


You should also set Firefox to "compact" and "dark mode". Those two options are available under menu > customize.
In my case I have installed the firefox theme HUMBLE GRUVBOX, it is the one I have instead of "dark mode", you can get it in "Add-ons and themes".

### Startpage

For the home page open firefox and drag the index.html file from "/home/XXXX/.firefox/XXXXXXX.default-release/chrome/startpage/index.html".
Close firefox and open it again, whenever you open it, it will come out with the home page,
Amy works that way for me.
Enjoy!

### Panel-Tint2

Icon-Left:

Icon: rofi spear
Icon: launches urxvt
Icon: thunar spear
Icon: launch firefox

Icon-Right:

Icon: left click play right click launches urxvt-ncmpcpp
Icon: launch rofi networkmanager-dmenu
Icon: volume
Icon: launch jgmenu exit, blogout, restart, shutdown