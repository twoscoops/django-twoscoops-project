========================
django-twoscoops-project
========================

A project template for Django 1.5.

Creating your project
=====================

To create a new Django project called '**icecream**' using django-twoscoops-project, run the following command (this assumes you have Django 1.5 or 1.4 installated aready)::

    $ django-admin.py startproject --template=https://github.com/twoscoops/django-twoscoops-project/zipball/master --extension=py,rst,html icecream

You can choose a different name by running the same command but replacing the word '**icecream**' with something else.

Installation of Dependencies
============================

First, make sure you are using virtualenv (http://www.virtualenv.org).

Then, depending on where you are installing dependencies:

In development::

    $ pip install -r requirements/local.txt

For production::

    $ pip install -r requirements.txt

*note: We install production requirements this way because many Platforms as a Services expect a requirements.txt file in the root of projects.*

Acknowledgements
================

Many thanks to Randall Degges