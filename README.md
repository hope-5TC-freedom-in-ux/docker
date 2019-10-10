This repository contains files to launch « La Petite Boîte Noire » with docker.

La Petite Boîte Noire is hosted at [https://lapetiteboitenoire.alp.tf](https://lapetiteboitenoire.alp.tf).

You might want to look at [the repository containing the application backend](https://github.com/hope-5TC-freedom-in-ux/backend) for information about « La Petite Boite Noire » backend.

# La Petite Boite Noire

« La Petite Boite Noire » is an immersive experiment into the dark face of websites.
The aim is to sensitize you to the questionable ethic of web giants.

There are currently two games implemented :
- [The registration](https://github.com/hope-5TC-freedom-in-ux/site_start)
- [IFFF article](https://github.com/hope-5TC-freedom-in-ux/challenge-article-ifff)

# How to use

Clone with submodules, then launch with docker-compose.

``` bash
git clone --recursive https://github.com/hope-5TC-freedom-in-ux/docker
docker-compose up -d
```

Then, the application will be available at [http://localhost](http://localhost).

# License

La Petite Boite Noire is licensed under the General Public License v3.
