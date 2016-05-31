# mamp-extension for MAMP PRO 3.X
##5.6.10

1. **Copy** `xxx.so` to `/Applications/MAMP/bin/php/php5.6.10/lib/php/extensions/no-debug-non-zts-20121212`
2. Add `extension=xxx.so` to the end of `php.ini` (Open MAMP click on File → Edit Template → PHP → PHP 5.6.10 php.ini)
3. **Restart** MAMP.

> phalcon.so memcache.so swoole.so

##7.0.0
1. **Copy** `xxx.so` to `/Applications/MAMP/bin/php/php7.0.0/lib/php/extensions/no-debug-non-zts-20151012`
2. Add `extension=xxx.so` to the end of `php.ini` (Open MAMP click on File → Edit Template → PHP → PHP 7.0.0 php.ini)
3. **Restart** MAMP.

> phalcon.so redis.so memcache.so swoole.so
