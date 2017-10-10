[![Build Status](https://travis-ci.org/zeroincombenze/web.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/web)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/web/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/web?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/web/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/web/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/web/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

.. image:: https://img.shields.io/badge/license-LGPL--3-blue.svg
================================================================
   :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
   :alt: License: LGPL-3

DarkroomJS Image Editing for Web
================================

This module provides a `DarkroomJS`_ (v2.0.1) web widget for use with image 
fields. It also adds a Darkroom button to the normal image widget, which can 
be used to edit the image via Darkroom in a modal.

.. _DarkroomJS: https://github.com/MattKetmo/darkroomjs 

The widget currently supports the following operations and can be extended to 
allow others:

* Zoom and pan
* Rotate
* Crop
* Step back in history client-side (before save)
 
Installation
------------





Configuration
-------------





Usage
-----

-----

-----

-----

-----

-----

=====

After installing the module, you can use it in the following ways:

* Specify the ``darkroom`` widget when adding an image field to a view. 
  Configuration values can be provided using the ``options`` attribute::

  <field name="image" widget="darkroom" options="{'minWidth': 100}"/>

  The widget passes options directly through to DarkroomJS, which supports the 
  following:

  * minWidth
  * minHeight
  * maxWidth
  * maxHeight
  * ratio (aspect ratio)
  * backgroundColor

* Open a form view that contains an image in edit mode and hover over the 
  image widget. You should see a Darkoom button that can be clicked to open 
  the image in a Darkroom modal, where it can be edited and the changes can be 
  saved.

  .. image:: /web_widget_darkroom/static/description/modal_screenshot_1.png
     :alt: Darkroom Modal Screenshot 1
     :class: img-thumbnail
     :height: 260

  .. image:: /web_widget_darkroom/static/description/modal_screenshot_2.png
     :alt: Darkroom Modal Screenshot 2
     :class: img-thumbnail col-xs-offset-1
     :height: 260

Known Issues / Roadmap

* Darkroom modals are currently not supported during record creation

Known issues / Roadmap
----------------------





Bug Tracker
-----------






Bugs are tracked on `GitHub Issues <https://github.com/OCA/web/issues>`_. In 
case of trouble, please check there if your issue has already been reported. 
If you spotted it first, help us smash it by providing detailed and welcome 
feedback.

Credits
-------






Images

* Odoo Community Association: 
  `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.






### Contributors






* Dave Lasley <dave@laslabs.com>
* Oleg Bulkin <obulkin@laslabs.com>

### Funders

### Maintainer










.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
