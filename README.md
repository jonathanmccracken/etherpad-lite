# Fork of Etherpad 

Include common plugins and Libre Office [see original source code](https://github.com/ether/etherpad-lite)

[see changes](https://docs.etherpad.org/docker.html#via-libreoffice)

## Build
`docker build -t etherpad .`

## Run
`docker run -d -p 9001:9001  -v $home/etherpad:/opt/etherpad-lite/app etherpad`

## Publish 

uses standard github-actions to publish via ghcr
