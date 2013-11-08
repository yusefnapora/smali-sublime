## Smali Syntax Highlighting rules for Sublime Text & Textmate

[Smali](https://code.google.com/p/smali/) is a decompiled representation of [Dalvik][1] bytecode.  If you're interested in reversing or modifying Android code, you'll be dealing with smali at some point.  On Windows, [Notepad++](http://notepad-plus-plus.org/) users can install [syntax highlighting rules for smali](http://androidcracking.blogspot.com/2011/02/smali-syntax-highlighting-for-notepad.html), which makes the whole process much easier.

I'm more of an OS X/Linux guy myself, so I've used the Notepad++ rules to make a Sublime Text/TextMate syntax definition file.  There may still be some rough edges, but it is already much, much better than reading through the un-highlighted plain text.

### Installation
The Smali.tmLanguage file is the one you want to install.  You can ignore the Smali.JSON-tmLanguage file unless you want to modify the rules.

For Sublime Text 2, copy the Smali.tmLanguage file to your Packages/User directory. The location is dependent on your platform:

* **Windows**: %APPDATA%\Sublime Text 2\Packages\User
* **OS X**: ~/Library/Application Support/Sublime Text 2/Packages/User
* **Linux**: ~/.Sublime Text 2/Packages/User

For TextMate, I think you're supposed to put the Smali.tmLanguage file in ~/Library/Application Support/TextMate/Bundles -- Haven't used TextMate for years, sorry!

### Modifying
If you'd like to fix or change something (thanks!), [this guide](http://sublimetext.info/docs/en/extensibility/syntaxdefs.html) should be helpful.  

[1]: http://en.wikipedia.org/wiki/Dalvik_(software)
