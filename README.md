osh
===

**osh** is a script to automate the tasks involved in managing OpenStack instances.


How it works
------------

Instead of having to remember a bunch of flags, it'll prompt you for the values one at a time and run the result.


How to use it
-------------

### Set up ###

1. Install the [OpenStack command-line clients.][1] For **osh**, you'll need **nova** and **neutron**.

2. Clone this repo and move the *osh* file somewhere your `$PATH` environment variable will see it, like [/usr/local, if you've set it up.][2]

3. Authenticate beforehand. This script assumes you're already signed in.

### Run ###

1. `osh <task name>`.


[1]: http://docs.openstack.org/user-guide/content/install_clients.html "Install the OpenStack command-line clients"
[2]: http://hivelogic.com/articles/using_usr_local "Hivelogic - Using /usr/local"
