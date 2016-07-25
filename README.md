# doc_bds_vpn

1. install ubuntu
2. install cisco stuff
http://www.socsci.uci.edu/~jstern/uci_vpn_ubuntu/
3. download install script
https://vpn-dc1.blackducksoftware.com/+CSCOE+/logon.html#form_title_text
4. install chrome
http://www.tecmint.com/install-google-chrome-in-debian-ubuntu-linux-mint/
5. go to artifactory
http://artifactory.blackducksoftware.com/artifactory/simple/bds-release/com/blackducksoftware/hub/appmgr.hubinstall.full/
6. jira
https://jira.dc2.lan/
7. confluence
https://confluence.dc1.lan/
8. install hipchat

#mount for a specific user
# first get uid
id tschoots
mount -o nosuid,uid=1000,gid=1000 -t vboxsf hub_installers /mnt/hub_installers/

http://superuser.com/questions/196653/how-do-i-manually-mount-a-linux-file-system-read-write-as-a-normal-user
