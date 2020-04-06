# pillowMaker
Animal Crossing: New Horizons Pattern exporter / importer proof of concept.

A very early stages proof of concept for converting AC:NH pattern data to and from a standard PNG image format so that images can be directly edited / created inside a complete image editor such as GIMP or photoshop.

<img src="https://i.imgur.com/7bYWgqE.png" alt="drawing" width="200"/>
<img src="https://i.imgur.com/9TMCMoj.png" alt="drawing" width="350"/>

## How to run
python3 needs to be installed, along with the following modules:
- PIL
- tkinter

This can be achieve in debain linux variants by doing:

```bash
sudo apt install python3
```
```bash
python3 -m pip install PIL tkinter
```
Once the dependancies have been met the program can be run as follows:
```bash
python3 pillowMaker
```

Python is cross platform and this should work on windows.


**There are currently additional dependancies on using this PoC.**

The program can only process individual exported pattern datas currently. kwsch's brilliant save editor <a href="https://github.com/kwsch/NHSE">here</a> has the ability to export an individual pattern's data and reimport. Until I can get a handle on the crypto this dependancy will remain.

You also need to be able to export and reimport save data to and from a computer which requires a homebrew enabled switch. I currently use JKSV to export and reimport my save data since his is one of the few tools that supports device level saves at the moment. Get it <a href="https://github.com/J-D-K/JKSV/releases">here</a>
