# i3block-scripts
Scripts used for i3block integred with i3bar

## xlockctl
A tools to manage easily a xautolock while regarding media or what else 

You can add thes line to you i3block.conf
```
# Xlock
#
# use xlockctl to manage button
[xlock]
label=XLOCK
command=xlockctl status; [[ -z "${BLOCK_BUTTON}" ]] || xlockctl auto
separator=true
interval=1
```
