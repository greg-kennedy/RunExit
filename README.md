# RunExit
`RUNEXIT.EXE` is a simple 16-bit Windows utility intended to run a single application and immediately exit Windows after that application quits.

# Origins
This is a fork of version 1.1 of the application (26th May 2013), written by [Steven Henk Don](https://www.shdon.com/about).

https://www.shdon.com/software/tools  

https://www.shdon.com/files/runexit.zip  

This commit contains [the original source code of version 1.1](https://www.shdon.com/files/runexit.src.zip), and has been redistributed here with the permission of Steven.

# Usage

Download `RUNEXIT.EXE` from the releases page and copy it to your system; these examples will assume that you save it to `C:\RUNEXIT\RUNEXIT.EXE`.

`win C:\runexit\runexit.exe [path to application] [optional application parameters]`

## Example 1
Run application `C:\MPS\GPM\GPM.EXE` with no additional parameters.

`win C:\runexit\runexit.exe c:\mps\gpm\gpm.exe`

## Example 2
Run application `C:\GAMES\MYGAME\GAME.EXE` with parameter `/cheatmode`

`win C:\runexit\runexit.exe c:\games\mygame\game.exe /cheatmode`

# Building from Source

1. Use a Windows 3.1 system
2. [Install Borland Delphi 1.00](https://winworldpc.com/download/c2b3c3be-c38a-e280-b00b-c38711c3a5ef)
3. Open project `RUNEXIT.DPR`