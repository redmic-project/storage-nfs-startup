# nfs-startup

Populate NFS resources, with directories and specific ownership

## Define startup directories

You can set `NFS_STARTUP_DIRS` variable in order to create directories for the first time.

It is a list of `<directoryName>:<uid>:<gid>` separated by spaces, where `uid` and `gid` are optional.
