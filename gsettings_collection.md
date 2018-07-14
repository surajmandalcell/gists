# Elementary OS Specific

### Bring back minimize and maximize buttons
`gsettings set org.pantheon.desktop.gala.appearance button-layout 'appmenu:minimize,maximize,close'`

### Set global dark theme (not gsettings)

To set the global dark theme from the command line, first navigate to a Terminal of your choice and then from within the shell emulator ...

Navigate to your home directory:

 `cd ~`

Create a new file called settings.ini inside of the GTK 3 directory:

 `nano ~/.config/gtk-3.0/settings.ini`

Enter the following fields into the configuration file:
```ini
[Settings]
gtk-application-prefer-dark-theme=1
```
Write the changes to disk by pressing control + x, then press y, then enter.
