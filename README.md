Wuchubuzai JavaScript SDK
http://www.wuchubuzai.com/

This repository contains the open source JavaScript SDK that allows you to utilize Wuchubuzai on your website.

Requirements
------------
jQuery 1.6.4 -- http://jquery.com/ || http://code.jquery.com/jquery-1.6.4.min.js
(Tested successfully with jQuery v1.7.1)

Example Usage
-------------

http://jsfiddle.net/wuchubuzai/vxcqW/   -- Sets environment, gets API url, performs a GET request against the 'reference' object
http://jsfiddle.net/wuchubuzai/JL2St/4/ -- Load the API with the SEARCH argument and no rest_key to force error
http://jsfiddle.net/wuchubuzai/d2fGq/   -- Authenticate with username/password to obtain rest_key and other information from authentication

A two step example is now available, which first Authenticates and then makes a second request with valid UID and RestKey to retrieve a list of "user_counters":
http://jsfiddle.net/wuchubuzai/ZU7Tu/

© wuchubuzai | 无处不在 2013
