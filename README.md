# BukkitToTwitter

## Overview

BukkitToTwitter is a simple plugin that posts tweets to Twitter from your Bukkit server. It automatically tweets when the server starts and stops, and tweets whenever a player joins or leaves the game. Staff can also post custom tweets directly with the `/tweet` command.

Example: https://twitter.com/DKBotMC

## Installation

Drag and drop BukkitToTwitter.jar into your servers plugin directory.

## Configuration

On first run, BukkitToTwitter generates a `config.yml` with the following options, which must be filled in with your Twitter app credentials:

| Option | Description |
| --- | --- |
| consumerKey | Your Twitter app's consumer key. |
| consumerSecret | Your Twitter app's consumer secret. |
| oAuthAccessToken | Your Twitter app's OAuth access token. |
| oAuthAccessTokenSecret | Your Twitter app's OAuth access token secret. |
| dateFormat | The date format used to timestamp each tweet, e.g. `dd/MM/yyyy HH:mm:ss`. |

## Commands

| Command | Description | Permission |
| --- | --- | --- |
| /tweet <string> | Post a tweet. | bukkittotwitter.tweet |
