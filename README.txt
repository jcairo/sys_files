This repo contains system settings files.

You can place any system setting files you like in here and symlink them
from ~/ using ln -s /path/to/file path/to/symlink

All files inside the repo should sit in .sys-files and each file in the folder
should be symlinked. For ex

ln -s ~/.sys_files/tmux.conf ~/.tmux.conf
