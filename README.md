Packaging scripts for utox
=========================

Works on debian stable with pbuilder

only dependency should be pbuilder

copy pbuilder hooks and rc file to correct locations for your convenience, the shell hooks are mostly for debugging.

then install pbuilder and run the buildall script

packages will go to /var/cache/pbuilder/result and to /root/localrepo
