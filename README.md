# RGA Template Repository #
RGA files are game archives that prepared for JoiPlay. This repository contains official templates for rga files.

## File structure ##
RGA files contain game assets, icon and configuration file and are compressed as zip archive. 

## Configuration File ##
RGA files have a configuration file (game.cfg) which contains game information. JoiPlay parses configuration file and uses parameters to show game information and process game files. Supported parameters are title, id, execFile, icon, version and type. title and type parameters are needed and others are optional. game.cfg.sample can be used as an sample file.

## How to ##
Templates for officially supported game types can be used for quick start. These steps can be followed to create a RGA file;
1. Open folder which contains game files.
2. Extract game files if they are compressed as a executable file.
3. Create configuration file (game.cfg) inside game folder.
4. (Optional) Delete unnecessary files.
5. Select all folder/files and compress them as a zip archive.
6. Rename file extension to rga.
