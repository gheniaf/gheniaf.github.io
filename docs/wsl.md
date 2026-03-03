---
layout: default
title: WSL
parent: Setups
nav_order: 1
---

## Prerequisites
1. Search for "Turn Windows features on or off" in the Start menu.
2. Check the boxes for Windows Subsystem for Linux and Virtual Machine Platform.
3. Click OK and restart your computer.

## Installation
Run Windows Command Prompt as administrator (or run `[Win] + X` then `I`).
To see available distributions:
```shell
wsl --list --online
```
Install a WSL distribution:
```shell
wsl --install -d <DistroName>
```

## Post-Installation
List installed WSL distributions:
```shell
wsl --list
```
Launch a specific WSL distribution:
```shell
wsl -d <DistroName>
```
Set default distribution:
```shell
wsl --setdefault <DistroName>
```
