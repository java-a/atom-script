# Script-Fudan

**Run code in Atom without encoding errors!**

## Why should I use `Script-Fudan` over `Script`?

Note that this is a fork of [rgbkrk/atom-script](https://github.com/rgbkrk/atom-script). This package solved Chinese encoding errors when running Java programs under Windows with Chinese language setting. If you are using macOS or *nix or using another system language, this fork is not for you.

解决在中文 Windows 系统下使用 [atom-script](https://github.com/rgbkrk/atom-script) 插件运行 Java 程序时出现的编码错误，包括中文报错信息及中文输出乱码。

**Tips:** For further information about currently supported grammars, usage and development, please refer to [rgbkrk/atom-script](https://github.com/rgbkrk/atom-script).

## Installation

`apm install script-fudan` or search for `script-fudan` within package search in the Settings View.

## Command and shortcut reference

| Command                    | Mac OS X                            | Linux/Windows               | Notes                                    |
| :------------------------- | :---------------------------------- | :-------------------------- | :--------------------------------------- |
| Script: Run                | <kbd>cmd-i</kbd>                    | <kbd>shift-ctrl-b</kbd>     | If text is selected a "Selection Based" is used instead of a "File Based" run |
| Script: Run by Line Number | <kbd>shift-cmd-j</kbd>              | <kbd>shift-ctrl-j</kbd>     | If text is selected the line number will be the last |
| Script: Run Options        | <kbd>shift-cmd-i</kbd>              | <kbd>shift-ctrl-alt-o</kbd> | Runs the selection or whole file with the given options |
| Script: Run with profile   | <kbd>shift-cmd-k</kbd>              | <kbd>shift-ctrl-alt-b</kbd> | Runs the selection or whole file with the specified profile |
| Script: Close View         | <kbd>esc</kbd> or <kbd>ctrl-w</kbd> | <kbd>esc</kbd>              | Closes the script view window            |
| Script: Kill Process       | <kbd>ctrl-c</kbd>                   | <kbd>ctrl-q</kbd>           | Kills the current script process         |
