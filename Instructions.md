---
author:
  name: Alan Greenwell
  email: alan@ghostdogs.co.uk
description: 'Hackintosh Build using OpenCore 0.5.6 on Gigabyte Z370'
keywords: ["Mac", "OpenCore", "Gigabyte", "Instructions"]
license: '[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0)'
published: 2020-March
modified_by:
  name: Alan Greenwell
title: 'Hackintosh Build OpenCore 0.5.6'
contributor:
  name: Alan Greenwell
  link: 
external_resources:
  - '[website](https://ghostdogs.co.uk)'
---

# Opencore 0.5.6 on Gigabyte Z390 Motherboards

## Build Bootable Drive

## Gather files

1. Cataline 10.15.3 installer must be downloaded from the Apple Store.
2. AML files have been generated
3. Kexts have been put in place
4. Drivers are in place

All of this has been done and placed on the USB stick.

## Change boot paramaters

The BIOS entries need to be changed and due to the versions moving things around you will need to find the following

1. Vt-d
2. Boot mode - Windows 8/10 WQHL
3. 

## Installation

{{< note >}}
These steps can be completed several times if necessary.
{{< /note >}}

{{< caution >}}
You will be erasing a disk and all its contents during these steps.
{{< /caution>}}

This becomes a little hit and miss due to specifics of each machine appearing in different places

First part if to switch machine on and keep pressing F12 until you see the boot select menu. Select the SanDisk EFI partition.
This will boot and the screen will have text streaming past for a few minutes. It should end with and Apple logo and progress bar followed by the installation dialogue boxes.

Follow the normal process of erasing the install disk using disk utility and then quiting disk utility and installing the OS.
This should go fine and don't worry too much about reboots, they will happen when needed and even a crash on Apple kit is normal.

After the first reboot you will see a simple text based menu with a number of options. 