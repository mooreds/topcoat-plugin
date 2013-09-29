topcoat-plugin
==============

This is a plugin that adds the Topcoat.io CSS to your project. Currently adds Topcat 0.7.5.

You can use this to pull topcoat into your Cordova application like so:

    cordova plugin add https://github.com/mooreds/topcoat-plugin

and then add this line to your index.html file:

     <link rel="stylesheet" type="text/css" href="topcoat/css/topcoat-mobile-light.min.css" />

and then use any of the topcoat classnames on your elements, as demoed here: http://topcoat.io/topcoat/topcoat-mobile-light.html

Note that you won't see any of these classes if you develop in the browser, so while doing that development, you should probably add to your HTML files (only for development, since [github is not a CDN](http://stackoverflow.com/questions/5502540/should-github-be-used-as-a-cdn-for-javascript-libraries/5503156#5503156).

     <link rel="stylesheet" type="text/css" href="https://raw.github.com/mooreds/topcoat-plugin/tree/master/www/css/topcoat-mobile-light.min.css" />


