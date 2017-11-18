# SublimeSettings

## Useful packages
- `PackageControl`: for installing/removing packages
- `AutoPEP8`: for formatting Python
- `BracketHighlighter`: --> see Quick Start Guide after installing for proper setup (should be done already in `Preferences.sublime-settings`)
- `SublimeAStyleFormatter`: for formatting C++
- `SublimeREPL`: interpreter for python, need to set up corresponding build system (shoule be done already in `Python3.6-REPL.sublime-build`)

## Build systems
- `Python3.6.sublime-build`: for python 3.6
- `Python3.6-REPL.sublime-build`: an python 3.6 interpreter within sublime text
~~- `C++`: for C++~~ (It's complicated to set up the vs compiler in sublime text, use terminal to compile instead (See next entry)!)
- change to cwd and enter `cl /EHsc xxx.cpp` to build, if successful, it prompts
```/output: xxx.exe
xxx.obj
```
Then, enter `xxx` (without the `.cpp ` extention to run)
