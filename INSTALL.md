Installing topline plugin
-------------------------

You need roundcube >= 0.9 installed.

The topline plugin has been tested against roundcube 0.9 and 1.4.1,
**is designed to work with larry based skins only**.

0. Download the latest version archive from
   https://github.com/roundcubevnz/roundcube-plugin-topline/tags

1. Uncompress it and move it to the roundcube plugins dir :

    tar xvjf roundcube-topline-0.0.7.tar.gz
    mv roundcube-topline-0.0.7 <path_to_roundcube>/plugins/topline

2. Add "topline" to the plugins list in <path_to_roundcube>/config/main.inc.php, 
   for example :

    $rcmail_config['plugins'] = array('topline',);

It works :)

for roundcube 0.8 see https://github.com/roundcubevnz/roundcube-plugin-topline/commit/6a5a1ed5d9a988b7248319b930a27927c59bc0fd

Configuration
-------------

You can customize some settings :

    copy config/config.inc.php.dist to config/config.inc.php
    edit config/config.inc.php to suit your needs
