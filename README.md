# script

Step 1 :

apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

Step 2 :

rm -rf setup2.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils wget screen curl && wget https://www.dropbox.com/s/suu3a2irdjr5dfy/setup2.sh && chmod +x setup2.sh && ./setup2.sh
