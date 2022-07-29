sudo sgdisk --zap-all /dev/sdb
sudo dd if=/dev/zero of="/dev/sdb" bs=1M count=100 oflag=direct,dsync
