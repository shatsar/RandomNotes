# Gnome Shell

## Send notifications from command line
``` notify-send ["<title>"] "<body>" ```

## Alt+Tab on current workspaces only
``` gsettings set org.gnome.shell.app-switcher current-workspace-only true```

## Enable workspaces on secondary monitor
``` gsettings set org.gnome.shell.overrides workspaces-only-on-primary false```
