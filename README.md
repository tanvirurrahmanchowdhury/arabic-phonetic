# Arabic Phonetic Keyboard for Linux (Modified)

This repository contains a slightly modified Arabic phonetic keyboard layout for Linux based on the work of [hydroEng](https://github.com/hydroEng/Arabic-Phonetic-Keyboard-Linux). While the original keyboard layout by [Omar al-Zabir](https://arabic.omaralzabir.com/home) is available for Windows and Mac, this version is tailored for Linux systems.

<br />The primary goal of this keyboard layout is to provide an intuitive and fluid typing experience for Arabic text input.
Installation Instructions

<br />Please note that this keyboard layout has been tested on Ubuntu 22.04. However, since it is a basic keyboard layout file, it should work on other Linux distributions as well, provided you are familiar with configuring keyboard layouts. hydroEng reported successful usage on Ubuntu 19.10.

## Follow these instructions to install the modified Arabic phonetic keyboard:

 <br />   Open your keyboard layout folder. On Ubuntu, you can do this by running the following command in the terminal:
```

cd /usr/share/X11/xkb/symbols
```
Find the file named 'ara' and create a backup by renaming it to 'ara_backup' or any other name of your choice. This step is essential in case you want to restore the default keyboard layout.

```
    sudo mv ara ara_backup
```

 <br />   Note: You will need sudo access for this step.

 <br />   Next, download the 'ara_' file from this repository and replace your old 'ara' file with it. For that, run the following command:
 ``` sudo cp path-to-your-download-directory/ara_ ./ # assuming you were in /usr/share/X11/xkb/symbols directory
```

 <br />   Restart your computer. After restarting, your QWERTY Arabic keyboard layout should be replaced with the phonetic keyboard.

 <br />   If you haven't already enabled the new layout, navigate to your system settings, go to 'Keyboard,' and select 'Input Sources.' Click the plus sign to add a new input source, then find 'Arabic (QWERTY)' and add it. Your new phonetic keyboard layout is now ready to use.

## List of Modifications

The following modifications have been made to the keyboard layout:

  1.  The letter 'ta marbuta' (ة) is now accessible directly with the 'x' key, eliminating the need for 'Shift + x.' Since it is a common letter.

  2.  The letter 'gain' (غ) has been moved to the 'g' key instead of 'Shift + g.'

  3.  The letter 'tha' (ث) has been moved to 'Shift + c.'

  4.  The letter 'lam-alif' (ﻻ) has been added and can be accessed with 'Shift + l.'

  5.  The hamza (ء) is now available with 'Shift + x.'

  6.  Arabic numerals 0 to 9 have been added for your convenience.

Enjoy a more intuitive Arabic typing experience with these modifications to the keyboard layout!
