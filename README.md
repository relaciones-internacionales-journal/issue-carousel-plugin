# OJS Plugin: insert issues carousel on journal's frontpage

- Issue Carousel Plugin<br>
- Source: Ictineo’s plugin: https://github.com/ictineo/ojs-issueCarousel
- Updated to OJS 2.4.6 from OJS 2.3.6 & added some minor changes
- Release date: August 08, 2015
- Author: Andy Mendioroz 

About
-----
This is an upgrade from Ictineo’s Issue Carousel OJS plugin: https://github.com/ictineo/ojs-issueCarousel.
Besides this upgrade, this changes were made:
 - Carousel will only use default issue image, but this can be changed copying Ictineo's code.
 - A list of all published issues will be displayed on the form, so user can choose which issue will be displayed on the Carousel.  

License
-------
See Ictineo’s Issue Carousel OJS plugin License: https://github.com/ictineo/ojs-issueCarousel

System Requirements
-------------------
Tested on OJS 2.4.6

Installation
------------
To install the plugin:
 - download the .zip file.
 - extract to a new folder.
 - upload to plugins > generic folder.

Use: see Ictineo’s Issue Carousel OJS plugin use: https://github.com/ictineo/ojs-issueCarousel

Known Issues/Limitations
---------
You may have to register the plugin manually. Go to your MySQL database and runn the following sql statement (you may have to change some values):

```
INSERT INTO `versions` (`major`, `minor`, `revision`, `build`, `date_installed`, `current`, `product_type`, `product`, `product_class_name`, `lazy_load`, `sitewide`)
VALUES
   (1, 0, 0, 0, '2015-06-18 12:32:12', 1, 'plugins.generic', 'issueCarousel', 'IssueCarouselPlugin', 1, 0)
```

Version History
---------------
1.0	- Initial Release
