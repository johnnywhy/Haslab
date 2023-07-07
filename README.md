# Microcontroller Replacements for the Haslab Spengler Series Proton Pack and Neutrona Wand

This repository outlines the full replacement of the stock microcontrollers which run the Proton Pack and Neutrona Wand while retaining the use and function of all existing switches and lights.

### "Yes, have some"...music!

Special thanks to Michael Klodzinksi for graciously allowing us to include his version of [Savin' The Day](https://www.youtube.com/watch?v=shJslMSAxE0) as a bundled music file to demo your awesome proton pack mods! Check out his other works at [michaelk.net](https://michaelk.net).

## Table of Contents

*"Ray, pretend for a moment that I don't know anything about metallurgy, engineering, or physics, and just tell me what the hell is going on." -Dr. Venkman*

That's alright, this will help you study. Below you will find the various guides to build out your new electronic brains, and maybe find some cool new features to implement as part of the addendums.

<hr>

<img src='images/gpstar_logo.png' width=50 align="left"/><h3>gpstar Proton Pack and Neutrona Wand PCB Guide</h3>This guide is intended for completing the connections and installation for the gpstar Proton Pack and Neutrona Wand PCB boards.

1. [Pack PCB](PACK_PCB.md)

1. [Wand PCB](WAND_PCB.md)

1. TBD: Wiring Loom, External Connectors, etc.

1. [Loading The Audio Files](AUDIO.md)

1. [Flashing Updates](FLASHING.md)

<hr>

<h3>DIY Arduino Build Guides</h3>

Considered the "legacy" guide to building your own solution using the Arduino platform.
This is an advanced build-out which requires opening all devices and performing a significant amount of soldering. **Proceed with caution, regardless of your skillset or abilities.**

1. [Bill of Materials](BOM.md)

1. [Power Requirements](POWER.md)

1. [Flashing/Uploading the code](ARDUINO_FLASHING.md)

1. [WavTrigger Configuration](WAVTRIGGER.md)

1. [Loading The Audio Files](AUDIO.md)

1. [Pack Setup](PACK.md)

1. [Wand Setup](WAND.md)

<hr>

<h3>Addendums</h3>

These apply to the normal operation and usage of the equipment regardless of which microcontroller boards you are using.

1. [Operation Manual](OPERATION.md)

1. [Advanced Configuration](ADVCONFIG.md)

1. [Audio Output](SOUND.md)

1. [Smoke Venting](SMOKE.md)

1. [Hose Examples](HOSE.md)

1. [Cyclotron Lights](CYCLOTRON.md) (Optional add-ons)

1. [N-Filter Vent Light](NFILTER.md) (Optional add-on)

1. [Wand Bar Graph](BARGRAPH.md) (Optional add-on)

1. [Frequently Asked Questions](FAQ.md)

## Walkthrough Videos ##

*"You know, it just occurred to me that we really haven't had a successful test of this equipment." -Ray Stantz*

Except that we have! Here is a [Walkthrough Video Contributed by JustinDustin](https://www.youtube.com/watch?v=mnfljGd5-uU) (YouTube, March 2023) showcasing several of the stock features in a converted pack/wand combination. Several optional features were implemented as part of this build using the Arduino platform.
[![Haslab Proton Pack Arduino Powered Walkthrough Video](https://img.youtube.com/vi/mnfljGd5-uU/maxresdefault.jpg)](https://www.youtube.com/watch?v=mnfljGd5-uU)

Additionally, this video covers several new updates in the months since, using the new gpstar controllers, as the [Optional Features and Menu Walkthrough](https://www.youtube.com/watch?v=ePXz99UawLQ) (YouTube, July 2023).
[![Optional Features and Menu Walkthrough Video](https://img.youtube.com/vi/ePXz99UawLQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=mnfljGd5-uU)

## Viewing MD Files

GitHub should automatically display these files with basic formatting, though to view these MD (MarkDown) files linked above with full formatting including color-coding, you can use a program such as [MarkdownPad](http://markdownpad.com/) (Windows) or [MacDown](https://macdown.uranusjr.com/) (MacOS). Alternatively, you may copy the contents into [an online viewer](https://markdownlivepreview.com/).

## Sound files

The sound effects files are combination of self made files for this project to ones from within the Ghostbusters community, etc. Apologies if it is forgotten to acknowledge where some of the files originate from.

## Licensing

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
