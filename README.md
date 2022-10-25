# Karabiner-Elements Complex Modifications

> My personal complex modifications for [Karabiner-Elements](https://karabiner-elements.pqrs.org/) on macOS.

My configuration consists of two layers.  One for navigation and one for symbols.  Each one is accessed via a key immediately accessible to the left and right little fingers.

The two layer keys set variables rather than using the meh/hyper method.  This avoids conflicts with system shortcuts that are impossible to deactivate (e.g. sysdiagnose).

### Pre-requisites

1. System shortcuts

	Create a shortcut in:

	System Preferences -> Keyboard -> Shortcuts -> App shortcuts -> All applications
	
	* Menu Title: Window->Zoom
	* Keyboard Shortcut: <kbd>left\_control</kbd> + <kbd>left\_command</kbd> + <kbd>z</kbd>
	

### Available Modifications:

1. Nav layer 
   
   This layer is accessed by holding the Capslock key and pressing a modifier: 

    * Hold <kbd>Capslock</kbd> → <kbd>Nav layer</kb>
    * Press <kbd>Capslock</kbd> → <kbd>Escape</kbd>

    Keyboard navigation with YUIO, HJKL, N.

    * <kbd>Y</kbd>/<kbd>U</kbd>/<kbd>I</kbd>/<kbd>O</kbd> →  <kbd>CMD</kbd>+<kbd>←</kbd>/<kbd>CMD</kbd>+<kbd>↓</kbd>/<kbd>CMD</kbd>+<kbd>↑</kbd>/<kbd>CMD</kbd>+<kbd>→</kbd>
    * <kbd>H</kbd>/<kbd>J</kbd>/<kbd>K</kbd>/<kbd>L</kbd> →  <kbd>←</kbd>/<kbd>↓</kbd>/<kbd>↑</kbd>/<kbd>→</kbd>
    * <kbd>M</kbd>/<kbd>,</kbd> →  <kbd>Back word</kbd>/<kbd>Forward word</kbd>
    * <kbd>N</kbd>/<kbd>.</kbd> → <kbd>Previous desktop</kbd>/<kbd>Next desktop</kbd>

    Adds mouse navigation using ESDF and clicks with WR and XCV.
    
    * <kbd>E</kbd>/<kbd>R</kbd> → Back/Forward
    * <kbd>D</kbd>/<kbd>F</kbd> → <kbd>Previous tab</kbd>/<kbd>Next tab</kbd>
    * <kbd>C</kbd>/<kbd>V</kbd> → <kbd>Previous Outlook pane</kbd>/<kbd>Next Outlook pane</kbd>

    Extra functionality:

    * <kbd>p</kbd> → Save screenshot (tap) / Copy screenshot to clipboard (long press)
    * <kbd>;</kbd> → Maximize window
    * <kbd>[</kbd> → Delete
    * <kbd>T</kbd>/<kbd>G</kbd>/<kbd>B</kbd> → Vol up/Vol down/Mute

2. Sym layer

   This layer is accessed by holding the quote key and pressing a modifier: 

    * Hold <kbd>'</kbd> → <kbd>Sym layer</kb>
    * Press <kbd>'</kbd> → <kbd>'</kbd>

    Available functionality:
    
    * Number row maps to function keys.
    * The first alpha row maps to numerals
    * The middle alpha row maps to the symbols that are normally on the number row
    * THe bottom alpha row maps to the symbols usually on the right of the keyboard.

    This layer adds numbers to the querty row and symbols to the botton two rows of letters.

### Usage:

1. Place files in `~/.config/karabiner/assets/complex_modifications/`

2. In **Karabiner-Elements-Preferences**, go to **Complex Modifications**, click **Add Rule** and click **Enable** for every entry under **Capslock Layer**.

Alternatively go to [karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/williumbillium/karabiner-elements/main/my-modifications.json](karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/williumbillium/karabiner-elements/main/my-modifications.json)

