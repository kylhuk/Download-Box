# Download-Box
A one-stop solution for downloading and managing movies and tvshows with docker (and a lot of other things which can be used in a self-hosted environment)

> [!CAUTION]
> This is currently getting a rework done, so don't use this branch unless you know what you are doing.

## Overview

## To Do
* ☑️ Clean up `docker-compose.yaml`
* ◼️ Write manual on how to use this
* ◼️ Draw new Overview-Diagram
* ◼️ Create Docker Container to copy basic confics into volumes
* ◼️ Integrate CrowdSec
* ◼️ Decide on LDAP solution and configure this
* ◼️ Update `docker-compose.yaml` so it can be used with env-variables without changing it
* ◼️ Add profiles so not all containers need to be started

# Manual
## Quick Start
Make sure you edit the `.env` file, so it suits your environment. After that you can bring this stack up by executing `docker-compose up -d`. Configs are not provided, so you have to manually configure all the software components.

If you are very new to all the tools, please check this [Installation Guide](https://github.com/sebgl/htpc-download-box#installation-guide) to get some help.

# FAQ
If you have any questions regarding this project, feel free to open up an issue and I'll gladly help you.

# Credits
Credits to @sebgl for the initial idea with his solution for HTPC computers (https://github.com/sebgl/htpc-download-box)
