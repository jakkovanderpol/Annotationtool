# Annotationtool
Annotation tool for online collaborative literature processing and interactive peer feedback

## Database
All tables are emptied except the help and language tables that contain system text strings and are loaded by key in the template files.

## Installatie (met gebruikte versies)
__Linux distro__
Distributor ID: Ubuntu
Description:    Ubuntu 14.04.5 LTS
Release:        14.04
Codename:       trusty

__Install Apache2__
Server version: Apache/2.4.7 (Ubuntu)
Server built:   Jul 24 2015 17:25:11

__Install PHP__
PHP 5.2.17 (cli) (built: Jul 19 2015 21:38:49)
Copyright (c) 1997-2010 The PHP Group
Zend Engine v2.2.0, Copyright (c) 1998-2010 Zend Technologies

__Install MySQL__
Server version: 5.5.53-0ubuntu0.14.04.1 (Ubuntu)

__Install imagemagick__
Version: ImageMagick 6.7.7-10 2016-11-29 Q16 http://www.imagemagick.org
Copyright: Copyright (C) 1999-2012 ImageMagick Studio LLC
Features: OpenMP

__Install ghostscript__
GPL Ghostscript 9.10 (2013-08-30)
Copyright (C) 2013 Artifex Software, Inc.  All rights reserved.
This software comes with NO WARRANTY: see the file PUBLIC for details.

__Install sendmail/postfix__

__Cron__
Setup crontab: */1 * * * * /var/www/annotatiesysteem.nl/convert.sh

__Install PEAR packages__
Installed packages, channel pear.php.net:
- Package          Version State
- Archive_Tar      1.3.11  stable
- Console_Getopt   1.3.1   stable
- DB               1.7.13  stable
- PEAR             1.9.4   stable
- Structures_Graph 1.0.4   stable
- XML_Util         1.2.1   stable

## Bestanden
-	./annotatiesysteem.nl/convert.sh and convert.php for converting the uploaded PDF files to GIF files that can then be annotated with the tool  (http://www.imagemagick.org/script/convert.php ).
-	./annotationtool.sql database file
-	Ghostscript server files: /var/lib/ghostscript
-	Extra fonts: /usr/share/fonts
-	Apache2 vhost file: ./ssl.annotatiesysteem.nl. Use your own ssl certificate.
