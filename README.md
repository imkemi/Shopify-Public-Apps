# Shopify-Public-Apps
1- Install Composer In Your Pc (linux)

(i)Run this in your command line: open your terminal
   curl -sS https://getcomposer.org/installer | php
   Or download composer.phar into your project root.
(ii)Install Dependencies
    Execute this in your project root.

(iii)php composer.phar install
    Autoload Dependencies
    If your packages specify autoloading information, you can autoload all the dependencies by adding this to your code:
    require 'vendor/autoload.php';
    for mor info please visit:- https://packagist.org/
2- Create your app. Use http://path-to-new_prj/oauth.php as the Callback URL
3- Get the app's credentials and update conf.php
4- Intall the app on a store by visiting http://path-to-new_prj/install.php?shop=example-shop.myshopify.com
5- An OAuth token for the shop should now be stored in the session. Check out the other .php files and see how they work.
