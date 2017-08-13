# Docksal - Pantheon Addons

## Installing

The following files should be installed in `~/.docksal/`

## stacks-pantheon.yml

*Install Location: `~/.docksal/stacks/`*

Contains docksal stack to be able to mimic Pantheon's environment.

## commands

*Install Location: `~/.docksal/commands/`*

Contains commands used for interaction with Pantheon and Docksal

### behat

```
fin behat
```

### terminus

```
fin terminus
```
Terminus wrapper to interact with terminus on cli environment. Can only be used in conjunction with our environments `inresonance/nginx`.


### pull

```
fin pull
```

Command used to pull most recent version of database and/or files from pantheon
