# sway2hypr

Attempts to enable some level of Hyprland compatibility for applications
written to work only with the sway IPC. This is accomplished by creating a
UNIX socket where sway's would normally be and linking it up to Hyprland's
own IPC with a translation layer slapped in between them.
