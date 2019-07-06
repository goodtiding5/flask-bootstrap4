================
Flask-Bootstrap4
================

.. image:: https://travis-ci.org/goodtiding5/flask-bootstrap4.png?branch=master
   :target: https://travis-ci.org/goodtiding5/flask-bootstrap4

Flask-Bootstrap4 packages `Bootstrap <http://getbootstrap.com>`_ into 
an extension that mostly consists of a blueprint named 'bootstrap'. 
It can also create links to serve Bootstrap from a CDN and works 
with no boilerplate code in your application.

Usage
-----

Here is an example::

  from flask_bootstrap4 import Bootstrap

  [...]

  Bootstrap(app)

This makes some new templates available, containing blank pages that include all
bootstrap resources, and have predefined blocks where you can put your content.

As of version 4, Flask-Bootstrap has a `proper documentation
<http://pythonhosted.org /Flask-Bootstrap>`_, which you can check for more
details.
