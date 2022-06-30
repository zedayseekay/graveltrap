---
layout: post
title:  "Welcome to GPU Driver Hell"
date:   2022-06-30 19:00:00 +0100
categories: drivers GPU
---
## Bootcamp drivers for MacBook 

iRacing is currently having some... difficulties... running on Bootcamp installations. 

The latest official AMD drivers for Apple Mac equipment can be found here:

[version 20.45.40.15 and 21.30.44.07](https://www.amd.com/en/support/kb/release-notes/apple-boot-camp)

The latter version is for 2019 PowerBooks; everything else is on the former.

## AMD microstutters

If you are using fTPM with Ryzen you may be affected by microstutters. Most motherboard manufacturers have now released a BIOS update, so if you're
- on Ryzen CPU
- have a mysterious stutter
- have fTPM enabled
you'll need to upgrade your *motherboard* BIOS.

AMD's release fix was AMD AGESA V2 1.2.0.7, so check the release notes for your motherboard's update to see whether it includes that release. If not you'll have to wait a while longer...

https://www.amd.com/en/support/kb/faq/pa-410
