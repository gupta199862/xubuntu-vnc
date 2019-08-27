# Headless Ubuntu/Xfce containers with VNC

## Project `accetto/xubuntu-vnc`

[Git Hub][this-github] - [Changelog][this-changelog] - [Wiki][this-wiki]

***

This project repository contains resources for building various Docker images based on [Ubuntu][docker-ubuntu] with [Xfce][xfce] desktop environment and [VNC][tigervnc] server for headless use.

The resources for the individual images and their variations are stored in the subfolders of the [Git Hub][this-github] repository and the image features are described in the individual README files. Additional descriptions can be found in the common project [Wiki][this-wiki].

The Wiki illustrates also the project's complete [image hierarchy][this-wiki-image-hierarchy].

### Git Hub subfolders / Docker image sets

#### [xubuntu-vnc][this-github-xubuntu-vnc]

Contains resources for building [accetto/xubuntu-vnc][this-docker-xubuntu-vnc] base images.

The images are streamlined and simplified versions of my other images [accetto/ubuntu-vnc-xfce][accetto-docker-ubuntu-vnc-xfce].

Several variations are available, including the one supporting overriding both the container user and the user group.

Examples of Dockerfiles for building stand-alone application images from scratch are also included.

#### [xubuntu-vnc-firefox][this-github-xubuntu-vnc-firefox]
  
Contains resources for building [accetto/xubuntu-vnc-firefox][this-docker-xubuntu-vnc-firefox] images with the current [Firefox Quantum][firefox] web browser.

Several variations are available, including the one supporting easy pre-configuration and copying of personal Firefox user preferences.

The images are streamlined and simplified versions of my other images [accetto/ubuntu-vnc-xfce-firefox-plus][accetto-docker-ubuntu-vnc-xfce-firefox-plus] and [accetto/ubuntu-vnc-xfce-firefox-default][accetto-docker-ubuntu-vnc-xfce-firefox-default].

#### [xubuntu-vnc-inkscape][this-github-xubuntu-vnc-inkscape]
  
Contains resources for building [accetto/xubuntu-vnc-inkscape][this-docker-xubuntu-vnc-inkscape] images with the free open-source vector graphics editor [Inkscape][inkscape].

Several variations are available, including the one with the current [Firefox Quantum][firefox] web browser.

#### [xubuntu-vnc-chromium][this-github-xubuntu-vnc-chromium]
  
Contains resources for building [accetto/xubuntu-vnc-chromium][this-docker-xubuntu-vnc-chromium] images with the open-source [Chromium][chromium] web browser.

#### [xubuntu-vnc-node][this-github-xubuntu-vnc-node]

Contains resources for building [accetto/xubuntu-vnc-node][this-docker-xubuntu-vnc-node] images with JavaScript-based development platform. It adds [Node.js][nodejs] platform, [npm][npm] package manager and distributed version control system [Git][git]. Additional [Node.js][nodejs] modules can be easily added using [npm][npm].

#### [xubuntu-vnc-typescript][this-github-xubuntu-vnc-typescript]

Contains resources for building [accetto/xubuntu-vnc-typescript][this-docker-xubuntu-vnc-typescript] images with JavaScript-based development platform. It adds [Visual Studio Code][vscode] developer editor and [TypeScript][typescript] programming language. Additional [Node.js][nodejs] modules can be easily added using [npm][npm].

#### [xubuntu-vnc-heroku][this-github-xubuntu-vnc-heroku]

Contains resources for building [accetto/xubuntu-vnc-js-heroku-postgresql][this-docker-xubuntu-vnc-js-heroku-postgresql] images with [heroku/CLI][heroku-cli] and [PostgreSQL][postgresql] for JavaScript-based development with [Node.js][nodejs], [npm][npm], [Git][git], [Visual Studio Code][vscode] and [TypeScript][typescript]. Additional [Node.js][nodejs] modules can be easily added using [npm][npm].

#### [utils][this-github-utils]
  
Contains utilities that make building the images more convenient.

- `util-hdx.sh`  
  
  Displays the file head and executes the chosen line, removing the first occurrence of '#' and trimming the line from left first. Providing the line number argument skips the interaction and executes the given line directly.
  
  The comment lines at the top of included Dockerfiles are intended for this utility.

Each utility displays the help if started with the `-h` or `--help` argument.

The utilities have been developed using my other utilities `utility-argbash-init.sh` and `utility-argbash.sh`, contained in the [accetto/argbash-docker][accetto-github-argbash-docker-utils] Git Hub repository, from which the [accetto/argbash-docker][accetto-docker-argbash-docker] Docker image is built.

## Issues

If you have found a problem or you just have a question, please check the [Issues][this-issues] and the [Wiki][this-wiki] first. Please do not overlook the closed issues.

If you do not find a solution, you can file a new issue. The better you describe the problem, the bigger the chance it'll be solved soon.

## Credits

Credit goes to all the countless people and companies, who contribute to open source community and make so many dreamy things real.

***

[this-github]: https://github.com/accetto/xubuntu-vnc/
[this-changelog]: https://github.com/accetto/xubuntu-vnc/blob/master/CHANGELOG.md

[this-wiki]: https://github.com/accetto/xubuntu-vnc/wiki
[this-wiki-image-hierarchy]: https://github.com/accetto/xubuntu-vnc/wiki/Image-hierarchy

[this-issues]: https://github.com/accetto/xubuntu-vnc/issues

[this-github-utils]: https://github.com/accetto/xubuntu-vnc/tree/master/utils/

[this-github-xubuntu-vnc]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc/
[this-docker-xubuntu-vnc]: https://hub.docker.com/r/accetto/xubuntu-vnc/

[this-github-xubuntu-vnc-firefox]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc-firefox/
[this-docker-xubuntu-vnc-firefox]: https://hub.docker.com/r/accetto/xubuntu-vnc-firefox/

[this-github-xubuntu-vnc-inkscape]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc-inkscape/
[this-docker-xubuntu-vnc-inkscape]: https://hub.docker.com/r/accetto/xubuntu-vnc-inkscape/

[this-github-xubuntu-vnc-chromium]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc-chromium/
[this-docker-xubuntu-vnc-chromium]: https://hub.docker.com/r/accetto/xubuntu-vnc-chromium/

[this-github-xubuntu-vnc-node]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc-node/
[this-docker-xubuntu-vnc-node]: https://hub.docker.com/r/accetto/xubuntu-vnc-node/

[this-github-xubuntu-vnc-typescript]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc-typescript/
[this-docker-xubuntu-vnc-typescript]: https://hub.docker.com/r/accetto/xubuntu-vnc-typescript/

[this-github-xubuntu-vnc-heroku]: https://github.com/accetto/xubuntu-vnc/tree/master/docker/xubuntu-vnc-heroku/
[this-docker-xubuntu-vnc-js-heroku-postgresql]: https://hub.docker.com/r/accetto/xubuntu-vnc-js-heroku-postgresql

[accetto-docker-ubuntu-vnc-xfce]: https://hub.docker.com/r/accetto/ubuntu-vnc-xfce
[accetto-docker-ubuntu-vnc-xfce-firefox-default]: https://hub.docker.com/r/accetto/ubuntu-vnc-xfce-firefox-default
[accetto-docker-ubuntu-vnc-xfce-firefox-plus]: https://hub.docker.com/r/accetto/ubuntu-vnc-xfce-firefox-plus

[accetto-docker-argbash-docker]: https://hub.docker.com/r/accetto/argbash-docker
[accetto-github-argbash-docker-utils]: https://github.com/accetto/argbash-docker/tree/master/utils

[docker-ubuntu]: https://hub.docker.com/_/ubuntu/

[chromium]: https://www.chromium.org/Home
[inkscape]: https://inkscape.org/
[firefox]: https://www.mozilla.org
[git]: https://git-scm.com/
[heroku-cli]: https://devcenter.heroku.com/articles/heroku-cli
[nodejs]: https://nodejs.org/en/
[npm]: https://www.npmjs.com/
[postgresql]: https://www.postgresql.org/
[tigervnc]: http://tigervnc.org
[typescript]: https://www.typescriptlang.org/
[vscode]: https://code.visualstudio.com/
[xfce]: http://www.xfce.org
