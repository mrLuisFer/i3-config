# i3wm Basic Config for Linux

## 📦 Setup
First of all, you need to install **i3wm** and **i3status**\
You can read the official documentation on how to install it

- [i3wm.org](https://i3wm.org/)
- [i3wm.org/downloads](https://i3wm.org/downloads/)
- [i3status.org](https://i3wm.org/docs/i3status.html)

Some of the commands you can run are the following:

If you use a system that uses `pacman` or `yay`, you can run the following command
```
yay -S i3wm i3status
```

Once installed you can clone the repository at the following path: (`~/.config/i3`)
```
mkdir ~/.config/i3 && cd ~/.config/i3
```

And run:
```
git clone -b main https://github.com/mrLuisFer/i3-config.git .
```

Now **log out** or **restart** to be able to change the window manager

it is highly recommended to have a **Nerd Font** installed this in order to have a better appearance and a good font style\
You can install one by one in the following link

- [nerdfonts.com](https://www.nerdfonts.com/font-downloads)

Or look for the command to install all (approximately +1gb)\
For example:
```
yay -S nerd-fonts-complete
```

Another recommended `dMenu` dependency for Arch users, you can install it by following the link:

- [suckless/dmenu](https://tools.suckless.org/dmenu/)
```
yay -S dmenu
```

Or a modern alternative is `Rofi`:

- [github/davatorium/rofi](https://github.com/davatorium/rofi)
- [archlinux/Rofi](https://wiki.archlinux.org/title/Rofi)

```
yay -S rofi
```

## 💻 Shortcuts
building...

### 📎 References
Links used to build this configuration:

- [https://i3wm.org/docs/](https://i3wm.org/docs/)
- [https://i3wm.org/docs/i3status.html](https://i3wm.org/docs/i3status.html)
- [https://thevaluable.dev/i3-config-mouseless/](https://thevaluable.dev/i3-config-mouseless/)
