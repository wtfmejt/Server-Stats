# Server-Stats
PHP Tool to easily get server information

Server-Stas is a group of premade easy to use functions that can return various types of information about your server.

## What information can i get with Server-Stats
With Server-stats you can get the folling information:

- Uptime - (Days, Hours, Mins, Secs)                                                             
- Total RAM - (Ammount in Kilobytes, MegaBytes, Gigabytes)                                  
- Available - RAM (Ammount in Kilobytes, MegaBytes, Gigabytes)                              
- Free RAM - (Ammount in Kilobytes, MegaBytes, Gigabytes)                                   
- Used RAM - (Ammount inKilobytes, MegaBytes, Gigabytes or %)                              
- CPU Useage - (As a %)                                                         
- CPU Info - (model, clock speed, cache ammount, cores)                
- Total Disk - Space (Ammount in Kilobytes, MegaBytes, Gigabytes)                           
- Total Free Disk Space - (Ammount Kilobytes, MegaBytes, Gigabytes)                      
- Disk Space Used - (Ammount Kilobytes, MegaBytes, Gigabytes or %)

##Function Names

Uptime:
```php
get_uptime($arg)
```
Ram:
```php
get_totalram($arg)
get_availableram($arg)
get_freeram($arg)
get_usedram($arg)
get_usedram2()
```

CPU:
```php
get_cpu_usage()
get_cpuinfo($arg)
```

HHD/SSD
```php
get_disktotalspace($arg)
get_diskfreespace($arg)
get_diskusedspace($arg)
get_diskusedspace2()
```

##How To Use
To use Server-Stas just use it as a php include on your project

```php
<?php include_once 'inc/serverstats.php' ?>
```
