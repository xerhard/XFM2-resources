# XFM2 resources

*for bringing in comments and/or additions you can post an* **Issue**

## The XFM2

The XFM2 Synthesizer Module is a 64-voice, 2-part, 6-operator FM Synthesizer with built-in effects processor, built on an FPGA chip.
It is the second generation of the XFM DIY Synthesizer Project by René Ceballos.

![The XFM2 Synthesizer Module](https://images.squarespace-cdn.com/content/v1/5d2c7309e3281e0001ef5655/1580208887777-8CBUTCQ4F8ECP4IU7OVB/ke17ZwdGBToddI8pDm48kPLerjwc9T00S19UIx4D7DV7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UWQaL5Zc965r8V2AH38PHUO8HP8IE1QJFP1I8jNvddiftNpR-oeFwj2Ae_lbqFbpxA/82940548_10213084820194329_1373900380894658560_o.jpg?format=1500w)

In short the XFM2 houses 2 independent 32 voice DX7's on steroids with an impressive sound quality.

However next to the possibility to mimic a DX7, the XFM2 is far more sophisticated with more complex modulation and feedback possibilities. If you are in doubt to build one, put a hundred bucks aside and read the manual.

The build is based on two pre-assembled development boards: the Digilent CMOD A7-35T (FPGA, USB, SRAM) and the Adafruit UDA1334A (I2S stereo DAC). 
This combination allows to get the module running in less than 10 components (about $99 total cost).

A user manual, installation guide, and the binaries that have to be loaded into the FPGA – using the provided instructions – are all made available.



[The XFM2 Synthesizer Module](https://www.futur3soundz.com/xfm2)

[Blog by René Ceballos](https://www.futur3soundz.com/da-blog)


The XFM2 is very well documented, but there is no GUI other then a spreadsheet to change parameters and set presets.

Therefore there are some projects started with several solutions to expand the possibilities of the XFM2

(In the mean time René Ceballos started another synth, the [XVA1](https://www.futur3soundz.com/) which is a virtual analog synth on the same hardware as the XFM2)



## Social

[XFM2 on Gearlutz](https://www.gearslutz.com/board/electronic-music-instruments-and-electronic-music-production/1297008-xfm2-fgpa-based-fm-synth-1.html)


## Hard and software projects

---

### PCB(s) for the XFM2/XVA1 Project

![3D Render](https://user-images.githubusercontent.com/884834/114622434-3efde000-9cae-11eb-929d-81e718634022.jpg)

Two XFM2/XVA1 PCB designs. One basic and an extended version

- [PCB(s) for the XFM2/XVA1 Project](https://github.com/bzeiss/xfm2-pcbs)

---

### dXFM2

![dXFM2 panel](https://github.com/architolk/fm-synth/blob/main/media/OPS-Volume.png)

A very interesting hardware implementation of a user interface for the XFM2 with a lot of visual feedback

See the video where Marco Brattinga demonstrates his hardware interface and explains his design philosophy

- [dXFM2](https://github.com/architolk/fm-synth)
- [dXFM2 demo](https://www.youtube.com/watch?v=aivNT1PkcIQ)

---

### XFM2_Editor_Librarian

![XFM2Editor GUI](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2Editor.png "XFM2Editor GUI")

A full desktop GUI for the XFM2 build on CTRLR https://ctrlr.org/ next to a DX7 to XFM2 converter.

- [XFM2_Editor_Librarian](https://github.com/rheslip/XFM2_Editor_Librarian)
- [Explanation of the XFM2 and demo of the XFM2_Editor_Librarian on YouTube](https://www.youtube.com/watch?v=Ny7eByV2aGQ)

---

### xfm2controller

![xfm2controller GUI](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2Qt.png "xfm2controller GUI")

A controller for the XFM2 Synthesizer using Qt 5.12, designed for RaspberryPi but also runs on Desktop (windows or Linux)

- [xfm2controller](https://github.com/ataristdude/xfm2controller)

---

### A simple Arduino-based XFM2 front panel

![XFM2Arduino GUI](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2Arduino.png "XFM2Arduino GUI")

an Arduino interface, as minimal as possible (but still user-friendly and useful)

- [XFM2interface](https://github.com/dylanmc/XFM2interface)

---

### XFM2UI

![XFM2UI](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2UI.jpeg "XFM2UI")

XFM2UI is an Arduino menu driven user interface for all XFM2 parameters. It is based on Teensy 4.0

- [XFM2UI](https://github.com/mlinton/XFM2UI)

---

### XFM2GUI

![XFM2GUI](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2GUI.png "XFM2GUI")

A multi-platform Desktop GUI in Java.
(The README is not in sync with the source code, but it runs at least on Linux)

- [XFM2GUI](https://github.com/SteadiestLlama/XFM2GUI)

---

### XFM2Java

![XFM2Java](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2Java.png "XFM2Java")

Richard Shipman's utility program to access XFM2 over serial. Build in single java class file.
- [XFM2Java](https://github.com/RichardShipman/XFM2Java)

---

### Xsynth

![Xsynth](https://github.com/xerhard/XFM2-resources/blob/master/images/Xsynth.png "Xsynth")

Another commandline tool, this is written in Kotlin by MacMannes.

He is now building a [hardware solution](https://lookmumnocomputer.discourse.group/t/xva1-user-interface-build-progress/2770) but now for the [XVA1](https://www.futur3soundz.com/), which is a virtual analog synth wich runs on the same hardware as the XFM2.

- [Xsynth on Github](https://github.com/MacMannes/XSynth)

---

### XFM2_patches
json patch files for the XFM2

- [XFM2_patches](https://github.com/xerhard/XFM2_patches)

### DX7syx-to-XFM2patches
Quick and dirty convertion of DX7 sysex files containing 32 presets into XFM2 json patch files.

- [DX7syx-to-XFM2patches](https://github.com/xerhard/DX7syx-to-XFM2patches)

### XFM2_GetterSetter  

![XFM2GetterSetter GUI](https://github.com/xerhard/XFM2-resources/blob/master/images/XFM2GetterSetter.png "XFM2GetterSetter GUI")

small JavaFX application to read/write & text edit XFM2 json patches.
Can be used as a platform independent alternative for the Excel spreadsheet delivered with the XFM2 documentation
- [XFM2_GetterSetter](https://github.com/xerhard/XFM2_GetterSetter)
