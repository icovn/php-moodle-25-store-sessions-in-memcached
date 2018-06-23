This repository for people who's still using Moodle 2.5.x. Moodel 2.5.x allows us storing sessions in "files" & "database". You can use this repository to store sessions in Memcached

To apply:
- Step 1: install Memcached server
- Step 2: install php-memcache extension
- Step 3: copy file lib/sessionlib.php to your project
- Step 4: appy config in config-dist.php to your project (line 34-38)
