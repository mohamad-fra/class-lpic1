# class-lpic1
mkdir /mnt/flashdrive
chmod 755 /mnt/flashdrive
fdisk -l
vim /etc/fstab
/dev/sdb1 /mnt/flashdrive auto  x-systemd.automount  0 0
mount /mnt/flashdrive
