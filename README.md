### How to install it

KWin needs custom KWindowSystem, so build and install it first

```sh
cd kwindowsystem
makepkg -i
```

Once you've done that, build and install KWin. Keep in mind that compiling KWin
may take some time if your computer is not very powerful

```sh
cd kwin
makepkg -i
```

Restart kwin_x11 by running `kwin_x11 --replace` command in KRunner.
