# Starlin_L2
[![License](https://img.shields.io/badge/license-CC%20BY--NC--ND--4.0-green?style=flat-square)](http://creativecommons.org/licenses/by-nc-nd/4.0) [![Pull Requests](https://img.shields.io/github/issues-pr-closed/katorlys/Starlin_L2?style=flat-square)](https://github.com/katorlys/Starlin_L2/pulls) [![Issues](https://img.shields.io/github/issues-closed/katorlys/Starlin_L2?style=flat-square)](https://github.com/katorlys/Starlin_L2/issues) [![Lines](https://img.shields.io/tokei/lines/github/katorlys/Starlin_L2?style=flat-square)](https://github.com/katorlys/Starlin_L2) [![Build](https://img.shields.io/github/workflow/status/katorlys/Starlin_L2/Build?style=flat-square)](https://github.com/katorlys/Starlin_L2/actions/workflows/build.yml) [![Codacy](https://img.shields.io/codacy/grade/b187c52b9b754ed8a670a3017201c05f?style=flat-square)](https://app.codacy.com/gh/katorlys/Starlin_L2)

## Introduction
Starlin_L2 Minecraft Spigot plugin made for StarlinWorld (星林宇宙) server.<br>

Main functions:<br>
- Prevent players from stucking in the Nether Portal when logging in.
![](https://cdn.jsdelivr.net/gh/katorly/Gallery001/plugins/2022-01-20_13.37.53.png)
- Prevent crops from being trampled.
![](https://cdn.jsdelivr.net/gh/katorly/Gallery001/plugins/2022-01-20_12.58.39.png)
- Record player's first-join time and monthly online time.
- Record the server's monthly players.
![](https://cdn.jsdelivr.net/gh/katorly/Gallery001/plugins/2022-01-20_14.52.png)

## Commands
- `/l2 time [player]` Displays the first-join time and total online time of the excutor or the specific player.

## Config
### timedata.yml
```yml
12345678-aaaa-bbbb-cccc-123412341234:   #Player's UUID
  name: Katorly                         #Player's ID
  first-time: 2022.01.01 00:00          #Player's first-join time
  total: 10.5                           #Player's total online time
  month-time:
    '2022': 19.2,11.5,0.7,8.0,3.5,0.0,7.2,9.9,48.3,0.0,1.1,0.6
```
This is generated by the plugin, do not edit if you don't know what you're doing.
### monthly.yml
```yml
'2022':     #Year
  '01':     #Month
  - Katorly #Playerlist
  - player2
```
This is generated by the plugin, do not edit if you don't know what you're doing.
