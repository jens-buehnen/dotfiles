#/usr/bin/env bash

wl-clip-persist --clipboard both &
noctalia &
xremap --watch ~/.config/xremap/config.yml &
for i in ~/.config/autostart/*; do
	gio launch "$i" &
done
