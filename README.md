# plesk-nginx-wprocket
My optimized settings for Plesk Onyx Nginx only and WP Rocket Plugin.

<b>Tested with Plesk Onyx Plesk Onyx Version 17.8.11 Update #35, December 22, 2018.</b>

This is a collection of various (tested) configuration snippets I've found in the last couple of years.

Whilst this might NOT be the most elegant solution, I found it to be extremely effective on a working server. 


I enclude  my additional nginx directives for Plesk Onyx.

Please add those here: 


HOSTING SERVICES --> DOMAINS --> yourdomain.com --> Apache & nginx Settings -> Additional nginx directives.


Additional notes:

* I'm using pure Nginx without Apache
* Tested with PHP 7.3
* WordPress 5.0.2


                                                +++++SOURCES USED+++++

One trick that'll make your WordPress site really fast. Yes, only one. (*well, I used more than one...):
https://codeable.io/one-trick-will-make-your-wordpress-site-really-fast/

various tewaks by EasyEngine:
https://easyengine.io/tutorials/nginx/

Nginx was compiled using script by VirtuBox
https://github.com/VirtuBox/nginx-ee

Perfect Nginx configuration for WP Rocket Plugin (used in additional nginx directives)
https://www.tinywp.in/wp-rocket-nginx-configuration/




