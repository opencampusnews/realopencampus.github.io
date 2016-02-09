Devfest Environment Setup
=====================================

[learn.adicu.com/setup](http://learn.adicu.com/setup)

Setup the programming environment on your computer for DevFest!

#### Building

Run the following in the root directory:

    ./build.sh

This generates `.html` files to be viewed in a browser.

### Deploying

Run the following command to deploy to [learn.adicu.com/setup](http://learn.adicu.com/setup) (requires SCP and access to adi-website on SSH):

    ./deploy.sh

#### Solutions

All solutions are available by section in the `solutions/` folder.

#### Using Vagrant

We support running with vagrant!  [Install and setup Vagrant](https://docs.vagrantup.com/v2/installation/index.html), and then:

    $ vagrant up # launches the box
    $ vagrant ssh # ssh into the box
    # You are now in the vagrant instance
    $ cd /vagrant # go to the code
    $ cd <solutions folder> # Ex: cd webdev-solutions/1.3.2\ Dynamic\ Routes
    # Run the solution # Ex: python app.py

#### Directory Structure

##### build/

This is where all the extra files needed to convert from markdown to HTML go. `build.sh` uses the files from this folder.
# realopencampus.github.io
