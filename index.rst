.. Sphinx Encoding Test documentation master file, created by
   sphinx-quickstart on Wed Nov 18 13:17:36 2009.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Sphinx Encoding Test's documentation!
================================================

.. toctree::
   :maxdepth: 2

Inline code::

    print(u"test é")

Included by an ``include`` directive

.. include:: fileutf8.py
    :literal:

.. include:: filelatin1.py
    :literal:
    :encoding: latin1

Included by a ``plot`` directive

.. plot:: ./fileutf8.py
    :include-source:
