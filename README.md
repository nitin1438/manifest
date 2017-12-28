Pixel Dust Project Manifest
===========================

## Initializing Repo ##

To initialize your local repository use

    repo init -u https://github.com/pixeldustproject-o/manifest.git -b o2
    
Then to sync up:

    "repo sync -jX" where X is the number of cores in your CPU

## Building ##

To start your build:
```bash
$ . build/envsetup.sh
$ lunch pixeldust_<device-name>-userdebug
$ make pixeldust -jX
```

    Where X is the number of cores you want to use for compiling.
