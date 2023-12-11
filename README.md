# rpi-lootarr
I am shamefully copying the name lootarr from another project. I really like it.

These are all the services I run for a media server on rpi 4.
Don't forget to set your .env file also.

Gluetun is great and works well with everything.


**REMEMBER to Create the directories***
# go to the directory where you want to store the media and config files and run:
# in my case the root directory was /mnt/md0/media-server/
mkdir -p config/{gluetun,ombi,prowlarr,heimdall,flaresolverr,qbittorrent,radarr,sonarr,plex}
mkdir -p media/
