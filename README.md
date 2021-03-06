# duckbot
[![GitHub License](https://img.shields.io/github/license/chippers255/duckbot)](https://github.com/Chippers255/duckbot/blob/main/LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/chippers255/duckbot)](https://github.com/Chippers255/duckbot/issues)
[![Build Status](https://img.shields.io/github/workflow/status/Chippers255/duckbot/DuckBot%20CI)](https://github.com/Chippers255/duckbot/actions/workflows/python-package.yml)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=Chippers255_duckbot&metric=code_smells)](https://sonarcloud.io/dashboard?id=Chippers255_duckbot)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=Chippers255_duckbot&metric=vulnerabilities)](https://sonarcloud.io/dashboard?id=Chippers255_duckbot)

A Discord bot for personal friend group. If you don't know me personally, consider how freaking weird it'd be to ask for the access token. Feel free to steal the code though.

## Development
The `scripts/build` directory contains scripts for development.

### Install Dependencies
Should be run whenever you pull from `upstream/main`.
```
. scripts/build/install.sh
```

### Run Tests and Linter
```
. scripts/build/test.sh
. scripts/build/lint.sh
```

### Run DuckBot
Requires `duckbut/.env` to be present, and the `TOKEN` environment variable to be set therein.
```
. scripts/duckbot.sh
```

###Installation Reference can be seen from here:

https://medium.com/better-programming/coding-a-discord-bot-with-python-64da9d6cade7


###Please note this works well with Python Versions 3.x or higher

###Ubuntu or MacOS is very much preferred

###In Windows use virtual box to use this

###You don't need to write code for Bot as the DuckBot code is already here

###Token can be generated from https://discord.com/developers/applications/812362721713848330/bot after you create the bot
