# repo-man

`repo-man` monitors Arch package repositories and updates the package database as packages are added or removed.

## Installation
'''sh
install -Dm0755 repo-man /usr/bin/repo-man
install -Dm0644 repo-man.service /usr/lib/systemd/system/repo-man.service
install -Dm0644 repo-man.conf-example /etc/repo-man.conf
systemctl daemon-reload
systemctl enable --now repo-man.service
'''
