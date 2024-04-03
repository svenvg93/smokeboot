# Smokeping - Bootstrap WebGui

A modern looking smokeping webgui.

## Screenshots

<img width="1475" alt="image" src="https://github.com/svenvg93/smokeping-bootstrap/assets/4511676/297b8060-2703-4855-b1d4-d5d441c90a9f">

## Features

- Cropping graphs
- Search Functions

## Roadmap

- Better support for small screen devices

## Installation - Bare metal

Replace the standaard page

```bash
 cd /etc/smokeping
 mv basepage.html basepage.html.bak
 wget https://raw.githubusercontent.com/svenvg93/smokeboot/main/basepage.html
```

## Installation - Docker

Use docker volumes to pass the into the docker container

Docker compose:

 ```bash
volumes:
- ./smokeping/basepage.html:/etc/smokeping/basepage.html
```

## Background change
Set the graph border to no in the Presentation file to have no borders and white background on the graphs

 ```bash
graphborders = no
```


## Acknowledgements

 - [tsumaru720/smokeping-bootstrap]([https://github.com/tsumaru720/smokeping-bootstrap])

