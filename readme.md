# Media Stack

This is my personal and selfhosted media stack. The stack that I use is the following:

- Jellyfin - streams media from the server to different clients
- Sonarr - manages TV shows (and anime) and sends requests to Jackett
- Radarr - manages movies and sends requests to Jackett
- Jackett - parses results coming from Radarr and Sonarr and finds available torrents for such media
- Transmission - torrent client to download media
- Jellyseerr - webapp for users to discover and request movies and TV shows
- Bazarr - scans available media and downloads subtitles for it

Everything is built around Docker and Docker Compose.
