<div align="center">
    <img src="https://github.com/treee111/wahooMapsCreator/blob/develop/docs/wahoo_elemnt_bolt.png" alt="wahooMapsCreator Logo" width=20%>
    <p>
        <a href="https://img.shields.io/badge/python-v3.6+-blue.svg" alt="Python">
            <img src="https://img.shields.io/badge/python-v3.6+-blue.svg" /></a>
        <a href="https://github.com/treee111/wahooMapsCreator/issues" alt="GitHub issues">
            <img src="https://img.shields.io/github/issues/treee111/wahooMapsCreator" /></a>
        <a href="#sponsors" alt="Contributions welcome">
            <img src="https://img.shields.io/badge/contributions-welcome-orange.svg" /></a>
    </p>
    <h1>Wahoo Maps Creator</h1>
</div>
A tool to create up-to-date maps for your Wahoo ELEMNT BOLT and BOLTv2, ELEMNT ROAM and Wahoo ELEMNT!

It runs on Windows, macOS as well as on Linux!

## Basic Overview
WahooMapsCreator is a tool to create maps based on the latest OSM data for your Wahoo devices. You can generate maps for the countries you like and you can control which OSM-tags are included.

The maps of your device may be old because Wahoo did not release a newer version in the last years.

OSM maps are constantly updated. With this program, the updated maps can be used on our Wahoo.

# Get it running
The instructions are intended to be suitable for beginners.

If anything is unclear or seams wrong, write an [:pencil2: issue](https://github.com/treee111/wahooMapsCreator/issues)!

## Download and Install required programs
Using Anaconda to setup a virtual Python environment is the fastest way to get wahooMapsCreator running!

[:rocket: Quick Start Guide for Anaconda](docs/QUICKSTART_ANACONDA.md#download-and-install-required-programs)

## Run wahooMapsCreator
via GUI
```
python wahoo_map_creator.py
```
via CLI
```
python wahoo_map_creator.py malta
```

A detailled description of the usage is documented [:computer: here](docs/USAGE.md#usage-of-wahoomapscreator)

## Copy the map-files to your device
When file-creation is finished, copy the maps files to your Wahoo device.

[:floppy_disk: docu](docs/COPY_TO_WAHOO.md#copy-maps-files-to-wahoo-device-)

## (Optional) Use a custom theme on your Wahoo
You can use a custom theme to control which OSM-tags are displayed on your device. Also in which zoom-level certain streets appear!

[:mag: docu](docs/TAGS_ON_MAP_AND_DEVICE.md#osm-tags-during-map-creation-and-on-your-device-)

## Contribution
You are welcome to provide input via Pull Requests, Issues or in any other way!
Discussion goes on:
- in this telegram channel: https://t.me/joinchat/TaMhjouxlsAzNWZk
- in this google group: https://groups.google.com/g/wahoo-elemnt-users/c/PSrdapfWLUE

More details can be found here: [CONTRIBUTING](.github/CONTRIBUTING.md#contributing-to-wahoomapscreator-)

## Thanks to
[@Intyre](https://github.com/Intyre)/Hank for the initial version of the script

@Higli and [@Ebe66](https://github.com/Ebe66)/ebo for the Windows- port