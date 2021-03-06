# CyberDrop Command Line Interface
![npm status](https://github.com/izqalan/CyberDrop-cli/workflows/Node.js%20Package/badge.svg)
![test status](https://github.com/izqalan/CyberDrop-cli/workflows/Test/badge.svg)
> Unofficial Cyberdrop.me Command Line Interface Album Downloader

## GUI Album Downloader
If you prefer gui downloader, I wrote a simple C# program for windows [here](https://github.com/izqalan/cy-client/releases). Just download the `.zip` and run the installer.

## Setup locally
Perform these steps to make initial setup of your work environment:
  1. Install the [Node.js](https://nodejs.org), it comes with the [NPM](https://docs.npmjs.com/) package manager
  
## Installation
```bash
$ npm install -g cyberdrop-cli
```

### Commands
```
get | g <album>               Download pictures from specified album
help [command]              display help for command
```

### Options

```
-p, --parallel      Download album images in parallel (faster but prone to corruption)
-o, --output        Downloaded album destinetion ( " . " for current directory)
-h, --help          Display all commands and options
```

## Usage
By default album will be stored into your local Downloads folder

```bash
$ cyberdrop-cli d [options] <album link> // old method

$ cy get [options] <album link>
```

use ``-o <directory>`` to specify outpu destination. ``-o .`` to output downloaded album to current working directory. 

```bash
$ cyberdrop-cli d -o <destination folder> <album link> // old method

$ cy get -o <destination folder> <album link>
```
