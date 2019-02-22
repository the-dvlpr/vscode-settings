# VSCocde Settings

The theme-specific settings are everything before the first line break in the [settings.json](/settings.json) file.

Everything after that is just preferential settings specific to my personal work machine.

# To Update Your Theme

Replace any theme settings you have in your settings file (`Preferences > Settings` or ⌘, on mac) with the theme portion (everything before the first line break) in the [settings.json](/settings.json) file. Upon saving you should be prompted to download the "One Dark Pro Vivid" theme which was the base for these cusomizations.

```json
"workbench.colorTheme": "One Dark Pro Vivid",
  "workbench.colorCustomizations": {
    "[One Dark Pro Vivid]": {
      "activityBar.background": "#0c0c0c",
      "editor.background": "#000000",
      "editorGroupHeader.tabsBackground": "#0c0c0c",
      "tab.inactiveBackground": "#000000",
      "tab.activeBackground": "#111111",
      "sideBar.background": "#050505",
      "sideBarSectionHeader.background": "#111111",
      "list.hoverBackground": "#22283b",
      "terminal.foreground": "#c8c8c8"
    }
  },
  "editor.tokenColorCustomizations": {
    "[One Dark Pro Vivid]": {
      "functions": "#ff0d86",
      "keywords": "#ff0d86",
      "strings": "#00f693",
      "numbers": "#faef00",
      "types": "#00fffb"
    }
  }

```
