<!-- DO NOT EDIT THIS FILE MANUALLY  -->
<!-- Please read the https://github.com/linuxserver/docker-snipe-it/blob/master/.github/CONTRIBUTING.md -->

[![linuxserver.io](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver_medium.png)](https://linuxserver.io)

[![Blog](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Blog)](https://blog.linuxserver.io "all the things you can do with our containers including How-To guides, opinions and much more!")
[![Discord](https://img.shields.io/discord/354974912613449730.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Discord&logo=discord)](https://discord.gg/YWrKVTn "realtime support / chat with the community and the team.")
[![Discourse](https://img.shields.io/discourse/https/discourse.linuxserver.io/topics.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=discourse)](https://discourse.linuxserver.io "post on our community forum.")
[![Fleet](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Fleet)](https://fleet.linuxserver.io "an online web interface which displays all of our maintained images.")
[![GitHub](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub&logo=github)](https://github.com/linuxserver "view the source for all of our repositories.")
[![Open Collective](https://img.shields.io/opencollective/all/linuxserver.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Supporters&logo=open%20collective)](https://opencollective.com/linuxserver "please consider helping us by either donating or contributing to our budget")

The [LinuxServer.io](https://linuxserver.io) team brings you another container release featuring:

* regular and timely application updates
* easy user mappings (PGID, PUID)
* custom base image with s6 overlay
* weekly base OS updates with common layers across the entire LinuxServer.io ecosystem to minimise space usage, down time and bandwidth
* regular security updates

Find us at:

* [Blog](https://blog.linuxserver.io) - all the things you can do with our containers including How-To guides, opinions and much more!
* [Discord](https://discord.gg/YWrKVTn) - realtime support / chat with the community and the team.
* [Discourse](https://discourse.linuxserver.io) - post on our community forum.
* [Fleet](https://fleet.linuxserver.io) - an online web interface which displays all of our maintained images.
* [GitHub](https://github.com/linuxserver) - view the source for all of our repositories.
* [Open Collective](https://opencollective.com/linuxserver) - please consider helping us by either donating or contributing to our budget

# [linuxserver/snipe-it](https://github.com/linuxserver/docker-snipe-it)

[![Scarf.io pulls](https://scarf.sh/installs-badge/linuxserver-ci/linuxserver%2Fsnipe-it?color=94398d&label-color=555555&logo-color=ffffff&style=for-the-badge&package-type=docker)](https://scarf.sh/gateway/linuxserver-ci/docker/linuxserver%2Fsnipe-it)
[![GitHub Stars](https://img.shields.io/github/stars/linuxserver/docker-snipe-it.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-snipe-it)
[![GitHub Release](https://img.shields.io/github/release/linuxserver/docker-snipe-it.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-snipe-it/releases)
[![GitHub Package Repository](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub%20Package&logo=github)](https://github.com/linuxserver/docker-snipe-it/packages)
[![GitLab Container Registry](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitLab%20Registry&logo=gitlab)](https://gitlab.com/linuxserver.io/docker-snipe-it/container_registry)
[![Quay.io](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Quay.io)](https://quay.io/repository/linuxserver.io/snipe-it)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/snipe-it.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=pulls&logo=docker)](https://hub.docker.com/r/linuxserver/snipe-it)
[![Docker Stars](https://img.shields.io/docker/stars/linuxserver/snipe-it.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=stars&logo=docker)](https://hub.docker.com/r/linuxserver/snipe-it)
[![Jenkins Build](https://img.shields.io/jenkins/build?labelColor=555555&logoColor=ffffff&style=for-the-badge&jobUrl=https%3A%2F%2Fci.linuxserver.io%2Fjob%2FDocker-Pipeline-Builders%2Fjob%2Fdocker-snipe-it%2Fjob%2Fmaster%2F&logo=jenkins)](https://ci.linuxserver.io/job/Docker-Pipeline-Builders/job/docker-snipe-it/job/master/)
[![LSIO CI](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=CI&query=CI&url=https%3A%2F%2Fci-tests.linuxserver.io%2Flinuxserver%2Fsnipe-it%2Flatest%2Fci-status.yml)](https://ci-tests.linuxserver.io/linuxserver/snipe-it/latest/index.html)

[Snipe-it](https://github.com/snipe/snipe-it) makes asset management easy. It was built by people solving real-world IT and asset management problems, and a solid UX has always been a top priority. Straightforward design and bulk actions mean getting things done faster.

[![snipe-it](https://s3-us-west-2.amazonaws.com/linuxserver-docs/images/snipe-it-logo500x500.png)](https://github.com/snipe/snipe-it)

## Supported Architectures

We utilise the docker manifest for multi-platform awareness. More information is available from docker [here](https://github.com/docker/distribution/blob/master/docs/spec/manifest-v2-2.md#manifest-list) and our announcement [here](https://blog.linuxserver.io/2019/02/21/the-lsio-pipeline-project/).

Simply pulling `lscr.io/linuxserver/snipe-it:latest` should retrieve the correct image for your arch, but you can also pull specific arch images via tags.

The architectures supported by this image are:

| Architecture | Available | Tag |
| :----: | :----: | ---- |
| x86-64 | ✅ | amd64-\<version tag\> |
| arm64 | ✅ | arm64v8-\<version tag\> |
| armhf| ✅ | arm32v7-\<version tag\> |

## Application Setup

Access the webui at `<your-ip>:8080`, for more information check out [Snipe-it](https://github.com/snipe/snipe-it).
**This container requires a MySQL or MariaDB server to connect to, we reccomend [ours](https://github.com/linuxserver/docker-mariadb)**

This container also generates an SSL certificate and stores it in
```
/config/keys/cert.crt
/config/keys/key.crt
```
To use your own certificate swap these files with yours. To use SSL forward your port to 443 inside the container IE:

```
-p 443:443
```

The application accepts a series of environment variables to further customize itself on boot:

| Parameter | Function |
| :---: | --- |
| `-e APP_ENV=` | Default is production but can use testing or develop|
| `-e APP_DEBUG=` | Set to true to see debugging output in the web UI|
| `-e APP_LOCALE=` | Default is en set to the language preferred full list [here](https://snipe-it.readme.io/docs/configuration#section-setting-a-language)|
| `-e MAIL_PORT_587_TCP_ADDR=` | SMTP mailserver ip or hostname|
| `-e MAIL_PORT_587_TCP_PORT=` | SMTP mailserver port|
| `-e MAIL_ENV_FROM_ADDR=` | The email address mail should be replied to and listed when sent|
| `-e MAIL_ENV_FROM_NAME=` | The name listed on email sent from the default account on the system|
| `-e MAIL_ENV_ENCRYPTION=` | Mail encryption to use IE tls |
| `-e MAIL_ENV_USERNAME=` | SMTP server login username|
| `-e MAIL_ENV_PASSWORD=` | SMTP server login password|

### PHP customization

This image uses our NGINX base image all configuration files for PHP and NGINX are located in `/config/php`. To overide any defaults please modify `/config/php/php-local.ini` IE for upload size: 

```
upload_max_filesize = 16
post_max_size = 16M
```

## Usage

Here are some example snippets to help you get started creating a container.

### docker-compose (recommended, [click here for more info](https://docs.linuxserver.io/general/docker-compose))

```yaml
---
version: "2.1"
services:
  snipe-it:
    image: lscr.io/linuxserver/snipe-it:latest
    container_name: snipe-it
    environment:
      - PUID=1000
      - PGID=1000
      - APP_URL=http://localhost:8080
      - MYSQL_PORT_3306_TCP_ADDR=<mysql host>
      - MYSQL_PORT_3306_TCP_PORT=<mysql port>
      - MYSQL_DATABASE=<mysql database>
      - MYSQL_USER=<mysql pass>
      - MYSQL_PASSWORD=changeme
      - TZ=US/Pacific
    volumes:
      - <path to snipe-it data>:/config
    ports:
      - 8080:80
    restart: unless-stopped
```

### docker cli ([click here for more info](https://docs.docker.com/engine/reference/commandline/cli/))

```bash
docker run -d \
  --name=snipe-it \
  -e PUID=1000 \
  -e PGID=1000 \
  -e APP_URL=http://localhost:8080 \
  -e MYSQL_PORT_3306_TCP_ADDR=<mysql host> \
  -e MYSQL_PORT_3306_TCP_PORT=<mysql port> \
  -e MYSQL_DATABASE=<mysql database> \
  -e MYSQL_USER=<mysql pass> \
  -e MYSQL_PASSWORD=changeme \
  -e TZ=US/Pacific \
  -p 8080:80 \
  -v <path to snipe-it data>:/config \
  --restart unless-stopped \
  lscr.io/linuxserver/snipe-it:latest
```

## Parameters

Container images are configured using parameters passed at runtime (such as those above). These parameters are separated by a colon and indicate `<external>:<internal>` respectively. For example, `-p 8080:80` would expose port `80` from inside the container to be accessible from the host's IP on port `8080` outside the container.

| Parameter | Function |
| :----: | --- |
| `-p 80` | Snipe-IT Web UI |
| `-e PUID=1000` | for UserID - see below for explanation |
| `-e PGID=1000` | for GroupID - see below for explanation |
| `-e APP_URL=http://localhost:8080` | Hostname or IP and port if applicable, be sure to define https/http |
| `-e MYSQL_PORT_3306_TCP_ADDR=<mysql host>` | Mysql hostname or IP to use |
| `-e MYSQL_PORT_3306_TCP_PORT=<mysql port>` | Mysql port to use |
| `-e MYSQL_DATABASE=<mysql database>` | Mysql database to use |
| `-e MYSQL_USER=<mysql pass>` | Mysql user to use |
| `-e MYSQL_PASSWORD=changeme` | Mysql password to use |
| `-e TZ=US/Pacific` | Specify a timezone to use EG Europe/London, this is required to run snipe-it |
| `-v /config` | Contains your config files and data storage for Snipe-IT |

## Environment variables from files (Docker secrets)

You can set any environment variable from a file by using a special prepend `FILE__`.

As an example:

```bash
-e FILE__PASSWORD=/run/secrets/mysecretpassword
```

Will set the environment variable `PASSWORD` based on the contents of the `/run/secrets/mysecretpassword` file.

## Umask for running applications

For all of our images we provide the ability to override the default umask settings for services started within the containers using the optional `-e UMASK=022` setting.
Keep in mind umask is not chmod it subtracts from permissions based on it's value it does not add. Please read up [here](https://en.wikipedia.org/wiki/Umask) before asking for support.

## User / Group Identifiers

When using volumes (`-v` flags) permissions issues can arise between the host OS and the container, we avoid this issue by allowing you to specify the user `PUID` and group `PGID`.

Ensure any volume directories on the host are owned by the same user you specify and any permissions issues will vanish like magic.

In this instance `PUID=1000` and `PGID=1000`, to find yours use `id user` as below:

```bash
  $ id username
    uid=1000(dockeruser) gid=1000(dockergroup) groups=1000(dockergroup)
```

## Docker Mods

[![Docker Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=snipe-it&query=%24.mods%5B%27snipe-it%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=snipe-it "view available mods for this container.") [![Docker Universal Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=universal&query=%24.mods%5B%27universal%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=universal "view available universal mods.")

We publish various [Docker Mods](https://github.com/linuxserver/docker-mods) to enable additional functionality within the containers. The list of Mods available for this image (if any) as well as universal mods that can be applied to any one of our images can be accessed via the dynamic badges above.

## Support Info

* Shell access whilst the container is running: `docker exec -it snipe-it /bin/bash`
* To monitor the logs of the container in realtime: `docker logs -f snipe-it`
* container version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' snipe-it`
* image version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' lscr.io/linuxserver/snipe-it:latest`

## Updating Info

Most of our images are static, versioned, and require an image update and container recreation to update the app inside. With some exceptions (ie. nextcloud, plex), we do not recommend or support updating apps inside the container. Please consult the [Application Setup](#application-setup) section above to see if it is recommended for the image.

Below are the instructions for updating containers:

### Via Docker Compose

* Update all images: `docker-compose pull`
  * or update a single image: `docker-compose pull snipe-it`
* Let compose update all containers as necessary: `docker-compose up -d`
  * or update a single container: `docker-compose up -d snipe-it`
* You can also remove the old dangling images: `docker image prune`

### Via Docker Run

* Update the image: `docker pull lscr.io/linuxserver/snipe-it:latest`
* Stop the running container: `docker stop snipe-it`
* Delete the container: `docker rm snipe-it`
* Recreate a new container with the same docker run parameters as instructed above (if mapped correctly to a host folder, your `/config` folder and settings will be preserved)
* You can also remove the old dangling images: `docker image prune`

### Via Watchtower auto-updater (only use if you don't remember the original parameters)

* Pull the latest image at its tag and replace it with the same env variables in one run:

  ```bash
  docker run --rm \
  -v /var/run/docker.sock:/var/run/docker.sock \
  containrrr/watchtower \
  --run-once snipe-it
  ```

* You can also remove the old dangling images: `docker image prune`

**Note:** We do not endorse the use of Watchtower as a solution to automated updates of existing Docker containers. In fact we generally discourage automated updates. However, this is a useful tool for one-time manual updates of containers where you have forgotten the original parameters. In the long term, we highly recommend using [Docker Compose](https://docs.linuxserver.io/general/docker-compose).

### Image Update Notifications - Diun (Docker Image Update Notifier)

* We recommend [Diun](https://crazymax.dev/diun/) for update notifications. Other tools that automatically update containers unattended are not recommended or supported.

## Building locally

If you want to make local modifications to these images for development purposes or just to customize the logic:

```bash
git clone https://github.com/linuxserver/docker-snipe-it.git
cd docker-snipe-it
docker build \
  --no-cache \
  --pull \
  -t lscr.io/linuxserver/snipe-it:latest .
```

The ARM variants can be built on x86_64 hardware using `multiarch/qemu-user-static`

```bash
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```

Once registered you can define the dockerfile to use with `-f Dockerfile.aarch64`.

## Versions

* **20.08.22:** - Rebasing to alpine 3.15 with php8. Restructure nginx configs ([see changes announcement](https://info.linuxserver.io/issues/2022-08-20-nginx-base)).
* **14.05.22:** - Add php7-sodium for v6.
* **12.04.22:** - Don't build development elements.
* **02.03.22:** - Rework init logic, do not show default compose.
* **29.06.21:** - Rebasing to alpine 3.14.
* **30.04.21:** - Rebasing to alpine 3.13, add artisan migrate on spinup.
* **01.06.20:** - Rebasing to alpine 3.12.
* **19.12.19:** - Rebasing to alpine 3.11.
* **28.06.19:** - Rebasing to alpine 3.10.
* **10.04.19:** - Add php deps for V4.7.0, ensure framework directories are available at build time.
* **10.04.19:** - Fix permissions for new bootstrap cache directory.
* **23.03.19:** - Switching to new Base images, shift to arm32v7 tag.
* **22.02.19:** - Rebasing to alpine 3.9.
* **31.10.18:** - Rebasing to alpine 3.8
* **05.08.18:** - Migration to live build server.
* **13.06.18:** - Initial Release.
