INTRODUCTION
------------
The readingtime module calculates the reading time of a node's body and
displays it as a field on the content node. This module requires that the node
you attach it to contain a body field, though it will safely ignore the node
if it does not.

From a usability/user experience standpoint, knowing the amount of time an
article will take to read may help a user make the decision whether to read it
now, bookmark it, or abandon the article entirely. What might look. at first
glance, like a large article may in fact only be a 3 minute read. This is much
more useful than just presenting the user with what appears to be a wall of
text and hoping they keep reading, and may keep them active on your site for
longer.

See http://briancray.com/posts/estimated-reading-time-web-design/ for a
discussion of the benefits of displaying reading time to your site visitors.

INSTALLATION
------------
 * Install as you would normally install a contributed drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.

CONFIGURATION
-------------
This module has no menu or global settings.  You will be able to configure the
field when adding it to a content type. When enabled, the field will display an
estimated reading time as part of the node's display.

MAINTAINERS
-----------
Maintained by Darren James Harkness - https://www.drupal.org/user/456800/