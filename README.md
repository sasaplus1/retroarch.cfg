# retroarch.cfg

my retroarch.cfg

## How to use

check ROM file name:

```console
$ ssh pi@xxx.xxx.xxx.xxx
$ ls -1 ~/RetroPie/roms/snes
RPG_GAME_1.sfc
RPG_GAME_2.zip
```

put config file to directory of ROM file:

```console
$ scp pi@xxx.xxx.xxx.xxx:~/RetroPie/roms/snes/RPG_GAME_1.sfc.cfg ./RPG.sfc.cfg
$ scp pi@xxx.xxx.xxx.xxx:~/RetroPie/roms/snes/RPG_GAME_2.zip.cfg ./RPG.sfc.cfg
```

see more details: [Hardcoded Configurations](https://retropie.org.uk/docs/RetroArch-Configuration/#hardcoded-configurations)

## License

The MIT license.
