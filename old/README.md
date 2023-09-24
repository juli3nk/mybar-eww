# MyBar Eww

set $eww "$HOME/.local/bin/eww"
set $eww_config "$HOME/.config/eww/"
exec_always --no-startup-id killall $eww; $eww -c $eww_config daemon; $eww -c $eww_config open bar
