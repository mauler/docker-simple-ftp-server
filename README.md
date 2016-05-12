simple-ftp-server
===================

Simple FTP server using pyftpdlib, for simple use case eg upgrade your wordpress plugins locally.

Based on:

https://github.com/giampaolo/pyftpdlib/blob/master/demo/basic_ftpd.py


How to use
----------

Simple command line usage:

```
docker run -p 11021:21 -it --rm -e FTP_USER=scott -e FTP_PASS=tiger -e mauler/simple-ftp-server
```

You can test using:
```
ftp localhost 11021
```

*Based on image m-creations/docker-openwrt-ftp*
