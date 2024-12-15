Drive layout:
- partition 1: Boot
- partition 2: btrfs

Top-level subvolumes:
- @root_debian_$date
- @flatpak
- @plex
- @docker
- @dockerfiles
- @var_log
- @apt_cache
- @snapshots
- @virtual_machines
- @swap
- @home

Additional packages:
- btrfs-progs
- btrfsmaintenance
- snapper
- docker
- flatpack
    - makemkv
    - handbrake
    - picard
    - firefox
    - mpv
    - mkvtoolnix
    - vlc
    - vlc bluray menus
    - makemkv plugin for VLC
- qemu
- htop
- mc
- ncdu
- pipx
    - beets
    - yt-dlp
- nvidia drivers
- tigervnc
- xfce4

Additional
- setup backports
- systemd services
