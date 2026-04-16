# rsync_backup
A bash script that uses rsync to backup directories to an external source.

script is in rsync_backup file
change the variables to suit
make the script executable by user who will execute, eg chmod 700
run using cron
crontab -e
for example using 
0 6 * * * /root/rsync_backup
root will run the script daily at 6am

