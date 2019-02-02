# Intro to Docker
## February 2019 - Girl Develop It (Boise)

## Pre-requisites

While no real pre-requisites are requried for the workshop, if you'd like to follow 
along with what we are doing in your own environment, you will want access to a docker 
instance, and I've included steps below for accessing Docker from major platforms

### Windows

Those of you who know me, know that I will always recomend an app management based approach 
to software deployments before I feed you a list of URLs and steps to follow ;)
Choco is that missing app management system for Windows users, and to find out more about it and 
get it installed, check out my [Intro to Chocolatey blog post](#).

For those of you with Choco already installed, from an elevated prompt run one of the following

#### Choco

For Windows 10 Pro/Ent/Edu users who can use Hyper-V:

`choco install docker-for-windows`

or for legacy Windows users, or users of home editions:

`choco install docker-toolbox`

#### Direct Download 

If you really don't want to use awesome app management tools like Chocolatey, you can still follow 
one of the guides from the Docker site to get the appropriate version for your platform

For Windows 10 Pro/Ent/Edu users who can use Hyper-V:

[Docker for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)

or for legacy Windows users, orusers of home editions:

[Docker Toolbox](https://docs.docker.com/toolbox/overview/)

### MacOS

Fortunatly, MacOS users don't have to worry about all that silly licensing fluff that Windows users do, so most users should be able to get the full Docker for Mac tools rather than the toolbox

Again, utilizing an application manager is the preferred method, so for MacOS that's usually [Homebrew](https://brew.sh/) (fairly simple instructions included on that site).

#### Homebrew

`brew cask install docker`

<<<<<<< HEAD
#### Direct Download

Again, custom tools aren't for everyone, and Docker.com has a well documented setup guide for MacOS users also:

[Docker for Mac](https://hub.docker.com/editions/community/docker-ce-desktop-mac)

=======
## Wutta Docker?

## Basic Docker commands

## Docker Lab 1

## Docker Lab 2

## Multi-stage builds
>>>>>>> ee48d0019319d5641fa06a476dbae8dba1efd17c
