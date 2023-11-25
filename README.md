# Docker - PHP - Template
The work by Gary Clarke gives a great tutorial for setting up a PHP Dockerized development environment.  It includes many details outside my personal use cases that are valuable and should be recognized.  I would strongly recommend viewing Clarke's tutorial if you have any questions regarding structure and implementation of the UW Asset Manager application, that uses this project as an initial template.

# Docker - PHP

[Docker PHP][1] is a **Docker and PHP** repository which accompanies [a YouTube tutorial][2].

Setup
------------

* For a standard build / setup, simply run
```docker compose up -d ```
* For a development build which exposes DB ports and includes Xdebug, you can run the dev-mode shell script like so
```sh ./bin/dev-mode.sh -d```
* To run with Xdebug enabled, run 
```XDEBUG_MODE=debug sh ./bin/dev-mode.sh -d --build```


Branches
-------------

Each branch (except main, dev, and branches prefixed with 'feature') corresponds to an accompanying series lesson.   

Contributing
------------

Docker PHP is an Open Source project and contributions are welcome. The 'main' branch is read-only as this should not differ from the tutorials so please send pull requests to the develop branch.

[1]: https://github.com/GaryClarke/docker-php
[2]: https://youtu.be/qv-P_rPFw4c
