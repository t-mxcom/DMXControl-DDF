# DMXControl-DDF

This repository contains a bunch of DDF (Device Definition File) files to be used with *DMX Control*, a free DMX based light control software.

[German DMXControl Website](https://www.dmxcontrol.org/)  
[English DMXControl Website](https://www.dmxcontrol.org/en/)

*DMX Control* uses a HAL (Hardware Abstraction Layer) to convert technical device specifications to a well defined set of logical functions that can be controlled through the applications UI.

After installing *DMX Control*, you'll get a bunch of DDFs installed with it but of course, there not every device can be included. Thus the providers of the application also run a *DDF Library* website, where you can search for additional DDFs and also publish your own.

[Gernam DDFLibrary Website](https://ddf.dmxcontrol.de/)

AFAIK, there is no English *DDF Library* website at the moment.

I currently own three DMX capable devices that I unfortunately couldn't find neither in *DMX Control* nor in *DDF Library*. So I decided to build my own DDFs.

## My devices

### Varytec Colors SonicStrobe

This is a LED based strobe.

It's main part is the bright flash and blinder in the center but it supports RGB effects in the background as well.

See the full description, images and DDFs [here](./devices/Varytec%20Colors%20SonicStrobe/docs/README.md).

### Ghost Yello 3 Colors

This is a LED based RGB laser.

It has a bunch of built-in patterns and automatic modes but also allows control of the functions via DMX.

See the full description, images and DDFs [here](./devices/Ghost%20Yello%203%20Colors/docs/README.md).

### eurolite LED KLS-180

This is a LED based 4-head RGB spotlight with 4 small strobes.

It has built-in programs and sound to light modes.

See the full description, images and DDFs [here](./devices/eurolite%20LEL%KLS-180/docs/README.md).

## Additional information

During development of the DDFs I learned a lot about DMX itself. And of course about *DMX Control* including DDF files.

As being a software developer, I needed to get an overview of the DDF structure and it's elements which brought me to build a reference for myself that I'm also sharend [here](./docs/DDF.md).

This reference is based on the official documentation in the [German DMXControl Wiki](https://wiki-de.dmxcontrol-projects.org/index.php?title=DDF_DMXC3) (unfortunately I don't know of an English version of the Wiki) and some try and error by myself.

As I'm not part of *DMXControl Projects e.V.* who is developing *DMX Control*, I cannot always keep my DDF documentation up to date. I'll do so only if I'm modifying the DDFs created by myself or adding something new.

So please always check back at the official sites!

[German DMXControl Projects e.V. Website](https://dmxcontrol-projects.org/)
