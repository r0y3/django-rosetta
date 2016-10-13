=======
Rosetta
=======

.. image:: https://travis-ci.org/mbi/django-rosetta.png?branch=develop
  :target: http://travis-ci.org/mbi/django-rosetta


Rosetta is a `Django <http://www.djangoproject.com/>`_ application that eases the translation process of your Django projects.

Because it doesn't export any models, Rosetta doesn't create any tables in your project's database. Rosetta can be installed and uninstalled by simply adding and removing a single entry in your project's `INSTALLED_APPS` and a single line in your main ``urls.py`` file.

Note: as of version 0.7.7 django-rosetta requires Django 1.7 or later. If you need support for earlier versions of Django (1.4+) you should stick to 0.7.6.

********
Features
********

* Database independent
* Reads and writes your project's `gettext` catalogs (po and mo files)
* Installed and uninstalled in under a minute
* Uses custom theme instead of Django's admin interface CSS


*************
Documentation
*************

Please refer to the `online documentation <http://django-rosetta.readthedocs.org/>`_ to install Rosetta and get started.
