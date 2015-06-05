marchev/librarian-puppet
=======================
Base images with `puppet` & `librarian-puppet` provisioned

Usage
---------------
1. Specify one the base image as a `FROM` instruction of your `Dockerfile`, e.g. `FROM marchev/librarian-puppet`
1. Create a `Puppetfile` in the same directory as `Dockerfile`
1. Create a `manifests/site.pp` file with your Puppet provisioning
