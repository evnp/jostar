Hotkey Setup
------------

## Iterm 2
1. Open `Preferences` -> `Keys` tab -> `Key Bindings` sub-tab
2. Press + icon in lower left
3. Click `Keyboard Shortcut` and press CTRL+J
4. Click `Action` and select `Send Text`
5. Click input box that appears below and enter `\e[Hj \n`

Let's break that down:
```
\e[H  :: this is an excape code that moves terminal cursor to start of line
j     :: this is the command used to invoke jo*
SPACE :: this puts a space between 'j' and any args already on the line
\n    :: this effectively simulates pressing ENTER key to execute the command
```

