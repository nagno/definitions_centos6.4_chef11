Build your boxfile with CentOS 6.4 and Chef 11
============================

You can build your CentOS 6.4 base box with Chef 11.

Modifications:
* libyaml is a requirement for Ruby 1.9.3, so now it is installed by base.sh
* Ruby install file is completely replaced, now it is downloads a pre-built Ruby 1.9.3 package for Centos 6.4 x86_64
* GB locale
* UK keyboard layout
* Install NFS Utils package
