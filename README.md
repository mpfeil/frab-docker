frab on Docker
==============

Run [frab](http://frab.github.io/frab/) on [Docker](https://www.docker.io/).

This repository triggers the [mpfeil/docker-frab](https://index.docker.io/u/mpfeil/docker-frab/) trusted build on the Docker index.
To run:

    docker pull mpfeil/docker-frab
    docker run -it -p 3000:3000 -t mpfeil/docker-frab

Then go to [http://localhost:3000](http://localhost:3000)