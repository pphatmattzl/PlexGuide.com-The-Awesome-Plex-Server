![N](https://preview.ibb.co/gdXE0m/Snip20171029_22.png)

# Automated Method

```
cd /tmp
sudo rm -r plexguide
sudo rm -r Version-*
sudo apt-get install unzip
sudo wget https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/archive/Version-3.5.zip /tmp
sudo unzip /tmp/Version-3.5.zip
sudo mv PlexGuide.com* plexguide && cd plexguide && cd 7*
sudo bash 01*
```

## Changes

Note:  As changes are made, files will be removed.  If not removed, continue to follow the rest of the guide or go with the old manual method at the bottom.

- Menu Interface Added
- Mass Install (Clean Server) or Individual Installs
- Installs SSH
- Installs Dependiences 
- Installs NetData 
- Installs Plex (Public)
- Installs SABNZBD

## Next:

- Sonarr
- Radarr
- Docker & Containers