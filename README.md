# @grundstein/guix-dev

development environment for our guix server environment.

for now, runs an alpine linux docker container and installs guix on top of it.

the irony is not lost on us.

## installation
```bash
git clone https://github.com/grundstein/guix-dev
cd guix-dev

# build the docker container
./bin/build.sh

# run the docker container. drops you into a shell (for now).
./bin/start.sh

```

