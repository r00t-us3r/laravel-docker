<h1 align="center">Welcome to laravel-docker 👋</h1

<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/r00t-us3r/laravel-docker#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/r00t-us3r/laravel-docker/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" target="_blank" />
  </a>
  <a href="https://github.com/r00t-us3r/laravel-docker/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://twitter.com/r00tus3r_">
    <img alt="Twitter" src="https://img.shields.io/twitter/follow/r00tus3r_.svg?style=social" target="_blank" />
  </a>
</p>

### About the project

> This is a simple repo that allows on to quickly setup a laravel project served using docker

### What's included?

> The following docker images are used in this project 
- [X] [PHP 7.2](https://hub.docker.com/_/php?tab=tags&page=1&name=7.2-fpm-alpine)  
- [X] [nginx](https://hub.docker.com/_/nginx?tab=tags&page=1&name=stable-alpine)  
- [X] [MySQL 5.7.22](https://hub.docker.com/_/mysql?tab=tags&page=1&name=5.7.22)  
- [X] [Laravel v6.4](https://laravel.com/)  

##### Please note

> At the time of writing, the current version of Laravel installed when using the composer ```create-project``` command was 6.4.0

> The repository will be updated periodically so that newer versions of laravel are available for use.  
A tag will be made referencing the version of laravel that is relavent to the tag.  
For example, the tag for the intial repo setup will be ```laravel-6.4```

### Building

> To run, simply use ```docker-compose up```  
This will build and start the docker containers

##### Please Note

> If you wish to use mysql, please uncomment the relevant lines in the ```docker-compose.yml``` file.  
By default, mysql is disabled as I personally use a dedicated machine on my network for databases.

### Usage

> Once the docker containers have been built and they are running, you can access the laravel "Front End" by visiting [http://localhost:8999](http://localhost:8999)

> The default port provided for nginx access is 8999 but this can be changed in the ```docker-composer.yml file```

### Issues

> If you have any issues, please do not heistate to open an issue on github and I will do my best to help you.  
Please be sure to read any existing issues to see if someone else has experienced the same issue (they may have had it resolved already)

### Contributing

> Anyone is welcome to contribute to this repo. I have created this repo to make initial setup of a laravel project a little easier.  
It is by no means a perfect example, but it'll do the job and get you started.

> If you want to add a feature yourself or have found a buy that you want to fix.  
Please create a fork, add your contribution / bug fixes and then open a Pull Request.

> If you wish to have a feature added, please open an issue with the title ```[Feature Request]```.  
I cannot guarantee that every feature request can be granted but if I am able to do so, I'll give it a good shot.

## 📝 License

Copyright © 2019 [r00t-us3r](https://github.com/r00t-us3r).<br />
This project is [MIT](https://github.com/r00t-us3r/laravel-docker/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_