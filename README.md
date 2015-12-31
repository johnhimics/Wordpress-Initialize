# pyInitWP.py #
Script that uses WP-CLI and a config file to setup
a wordpress installation


# Requirements
>> UNIX-like environment (OS X, Linux, FreeBSD, Cygwin); limited support in Windows environment
>> PHP 5.3.2 or later
>> WordPress 3.5.2 or later
>> Python


# Installing wp-cli #
Installing (And Upgrading)
First, download wp-cli.phar using wget or curl. For example:

curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
Then, check if it works:

php wp-cli.phar --info
To be able to type just wp, instead of php wp-cli.phar, you need to make the file executable and move it to somewhere in your PATH. For example:

chmod +x wp-cli.phar
sudo mv wp-cli.phar /usr/local/bin/wp
Now try running wp --info.

Upgrade using the same procedure.


# Usage #
Create a wpinit.json file in the root of a new WordPress installation
Run pyInitWP.py in the same directory
python pyInitWP.py

