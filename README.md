Ansible Role for Apache Tomcat
====================================

Ansible Role for Apache Tomcat

Requirements
------------

This role requires Ansible 2.8 or higher.

This role requires the `community.general` collection, which provides the `xml`
module used to apply the secure session cookie settings to `web.xml`. The
`lxml` python library is installed on the target host by the role itself.

This role was designed for CentOS 6.x, 7.x and 8,x, as well as Amazon Linux 2.

Role Variables
--------------


# ansible-role-tomcat