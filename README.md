# ToucheggKDE
TouchEgg configuration for Touchpad Gestures like MacOS/Windows for KDE Plasma. Finally, enjoy the multi-touch touchpad gesture goodness of MacOS in KDE Plasma!

## Installation
[Install touchegg first if you haven't already](https://github.com/JoseExposito/touchegg)   
```shell
git clone https://github.com/noiseredux2/ToucheggKDE.git
cd Touchegg*
mkdir ~/.config/touchegg
cp touch* ~/.config/touchegg/
```
**That's it!**

## Usage
### Swipe Gestures:
  - 3 Fingers UP: **Present Windows**   
  - 3 Fingers DOWN: **Show Desktop**   
  - 3 Fingers LEFT/RIGHT: **Switch Virtual Desktops**   
  - 4 Fingers UP/DOWN: **Control System Volume**   
  - [Browsers] 4 Fingers LEFT/RIGHT: **Go Back/Forward**
  ![untitled](https://user-images.githubusercontent.com/25067102/121768884-4b070080-cb7e-11eb-8657-bbbd570e5c2b.gif)

### Pinch Gestures:
  - 3 Fingers PINCH IN/OUT: **Desktops Grid View**   
  - 2 Fingers PINCH IN/OUT: **Zoom IN/OUT**
  - [Browsers] 4 Fingers PINCH IN/OUT: **Switch Tabs**

## Troubleshoot
If you're using OpenSUSE or other distros which don't have the `qdbus` package,
do this:
```shell
nano ~/.bashrc
````
Then at the end of the file, add: `alias qdbus=”qdbus-qt5”`   
Exit with Ctrl+O, Enter then Ctrl+X..
Then
```shell
source ~/.bashrc
```

## 
