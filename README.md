# Jellyfin setup for local testing and Kubernetes Helm chart

## Instruction - Local docker setup

1. Create the media folder and add movies/tv-shows/music to it.
2. Start the container.

    ```docker-compose up --build --force-recreate```
3. Go to http://0.0.0.0:8080 in your browser and setup your account and add libraries for movies/tv-shows/music (you will find all media in the /media folder when you chose a folder for your library).

## Kubernetes helm setup for Jellyfin

@TODO Add documentation for kubernetes helm chart deployment with local storage as storageclass.