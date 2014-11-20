## Synopsis

At the top of the file there should be a short introduction and/ or overview that explains **what** the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

## Usage
`chmac.sh <adapter>`

##nExample:
```
chmac.sh -r wlan0  -- this sets the mac address to be random
```

## Motivation

macchanger broke, so I decided to write a quick bash script to do the same thing.

Certain public wifi hotspots track you based on mac address. Sometimes your mac address is transported outside of the subnet you are on. I find this to be a little creepy.


## Installation

just download the file chmac and run it. This program is written in bash.

## TODO

Allow specification of hardware vendors.

## Contributors

@gunn4rl

## License

Public Domain.

