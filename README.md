# skUnity-Game-Night-Server

## About skUnity Game Night

Every month, skUnity hosts the skUnity Game Night. Where members of skUnity can come together and play a selection of games.

## About this repo

This repo is to provide a range of Minecraft games on a server hosted by skUnity.

## Contribution

Anyone can contribute to the repo and provide their PR's to existing files or submit new games. Please read the guidelines below.

## Guidelines

The GameManager.sk is the main script that functions as the lobby handler, leaderboard tracker, staff and player management, chat management. In the future, it might be broken into smaller files. All games will need to use essential functions from it.

Games must run their own checks to make sure they're the game being ran to prevent them having code ran when it's not that game. LavaRising.sk is a game that will be used but also an example of the standard.

The code you submit must be easily readable, functional, use the required functions from GameManager.sk, have no known bugs/exploits. 

#### Programming Standards

- Identation must use tabs, not spaces. 
- You must not use in-line ifs.
- Ideally break your code down into functions.
- You must use GameManager functions where possible.
- Your code should be flexible in setup of any arenas, no hardcoded values.
- Your messages must use the prefix found in GameManager.sk but with the "GameManager" text changed.
- Your messages must use &e for normal text, &c for warning text, &a for highlighting specific words in a message.
- Your commands must use GameManager_Is_Staff(player) if they're not a player command.
- Your code shouldn't override any other functions unless there is good reason.
- Your script may use the following addons: skript-reflect and SkBee only. If you need a specific addon added, contact BaeFell.

By submitting your code to the repo, you're agreeing that you give skUnity the permission to use your code, in part or full, in the script it was originally intended for or in other scripts developed by skUnity without any compensation of any sort. You release all rights and ownership of the code to skUnity. While this may seem extreme, due to previous cases in the Minecraft development envrioment, we are protecting ourselves.

## Support

**NO SUPPORT IS GIVEN FOR THESE SCRIPTS. NO LIABILITY IS ACCEPTED BY SKUNITY OR ANY CONTRIBUTORS. USE AT YOUR OWN RISK. DO NOT SEEK OUT SUPPORT FROM SKUNITY OR CONTRIBUTORS.**

Only support for developing the scripts and creating new games is provided by skUnity.
