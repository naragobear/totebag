# totebag
A repository to keep nice scripts that have been quite useful to me

# Usage
Just place the script of your choice in /usr/local/bin and run them!

# Scripts
dockerbuild
    A script to do the following: 
        1. Do a docker build based on the docker file on directory where the cript is being called from
        2. Write all the output to /var/loc/docker.log for easier debugging
    
    Usage : dockerbuild <friendlyname>
            e.g. dockerbuild makecligreatagain


dockertags
    A script to list all the versions of a particular docker image.
    Usage : dockertags <imagename>
            e.g. dockertags php