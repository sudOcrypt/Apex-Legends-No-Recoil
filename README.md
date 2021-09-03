# Apex-NoRecoil-2021

Apex Legends (1080p)

## AHK Script - Description
This repository contains an Autohotkey script to help you minimize weapon recoil. Your weapon is auto-detected by the script (no need to press the F key anymore! XD). The detection is based on a straightforward and naive strategy (I call it three-pixel-detection). It is pretty safe because all it does is just capture some pixels and then use mouse DllCall to move your mouse. Run the compiled version if you want more protection. Current support weapon: R99, R301, RE45, Flatline, Spitfire, Havoc, Volt, Devotion, L-Star, Hamlok, Prowler, Alternator, P2020 and Rampage.

R99, R301, RE45, Alternator, Flatline, Spitfire, Havoc, Volt, Devotion, L-Star, Hamlok, Prowler, P2020 and Rampage.

- Pros
  - simple 
  - out of the box 
  - support different language setting in game
- Cons
  - too many magic pixel position 
  - need lots of modification to support other resolution
  - not many people know how to code with AHK, not DIY friendly

## Python CLI - Description 
The repository also contains a Python version of the AHK script. It uses the Google Tesseract OCR and OpenCV to detect the weapon being used via key listener. The recoil-patterns are applied via win32api mouse_event. The program was built to be consumed as a CLI. The Python dir also contains a recoil-pattern creation tool which can be found in the modules dir. For more info please read the README in the python dir.

### [Python CLI - Details and Usage] (https://github.com/sudOcrypt/Apex-Legends-No-Recoil/tree/main/python)
- Pros
  - DIY friendl
  - Cool CLI 
  - Smart detection strategy
- Cons
  - detection based on OCR, only support English charactor
  - currently don't have as much as features as the AHK one 

## Contributing
It would be good if you can help me setup some more accurate recoil value or make the script support more weapons. Check the code and send me a pull request if you do so. I really appreciate that. 

