## Switch panel
With this package you can switch which panel should be displayed.

demo:
![xkbpsb1yju](https://user-images.githubusercontent.com/3492040/34440569-3c7651c4-ecb6-11e7-9396-8fea6a1db2b6.gif)


The package does not ship with any keyboard mappings. We recommend users add those keybinding you want. Example

```json
    {
        "keys": ["super+n"],
        "command": "ps_output_panel"
    },
    {
        "keys": ["super+m"],
        "command": "ps_output_panel_next"
    },
```


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `PanelManager` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.

