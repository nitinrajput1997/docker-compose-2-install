# docker-compose-2-install


# Create the docker plugins directory if it doesn't exist yet
```
mkdir -p ~/.docker/cli-plugins
```
# Download the CLI into the plugins directory
```
curl -sSL https://github.com/docker/compose/releases/download/v2.0.1/docker-compose-linux-x86_64 -o ~/.docker/cli-plugins/docker-compose
```
# Make the CLI executable
```
chmod +x ~/.docker/cli-plugins/docker-compose
```

# Check version
```
docker compose version
> Docker Compose version 2.0.1
```
