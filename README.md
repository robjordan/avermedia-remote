# avermedia-remote
Keycode map for Avermedia RM-FP IR remote (KODI, XMBC)

Developed using instructions from [here:](https://wiki.libreelec.tv/infrared_remotes)

Copy the keymap file to 
```
/storage/.config/rc_keymaps/avermedia_rm_fp
```

Install it and make it permanent like this:
```
ir-keytable -c -w /storage/.config/rc_keymaps/avermedia_rm_fp
echo "* * avermedia_rm_fp" > /storage/.config/rc_maps.cfg
```
