# nm-connect
toggle NetworkManager connections via searchable menu

# usage

```
$ nm-connect
[pick a connection with fzf]
$ nm-connect --gui
[pick a connection with rofi]
$ nm-connect --menu dmenu
[pick a connection with dmenu]
$ nm-connect connection_name # toggle connection noninteractively
```

# requirements

NetworkManager and `nmcli`

Python 3.6+

by default, fzf and rofi, but you can use a custom menu command, too
