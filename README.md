# Docker container for pgadmin4

Create a folder for settings and run the container

```
mkdir -p ~/pgadmin-data
docker run -it --rm -v ~/pgadmin-data:/pgadmin-data --net=host fergalmoran/pgadmin4:latest
```