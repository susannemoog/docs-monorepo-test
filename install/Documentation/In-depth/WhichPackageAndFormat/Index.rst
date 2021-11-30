﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _which-package-and-which-file-format:

Which Package and which File Format?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TYPO3 is available in various "packages" and each package is available
in different formats.


.. _which-package-to-use:

Which Package to use
""""""""""""""""""""

You can download the introduction package, the blank package, the
source package and the dummy package.

An overview of all available packages and versions can be found at
`http://typo3.org/download/
<http://typo3.org/download/>`_


.. _introduction-package:

Introduction Package
~~~~~~~~~~~~~~~~~~~~

The introduction package is a complete demo website. It contains the
contents of the source package, the dummy package and a lot of default
content for testing and learning. Please try this, if you are a
newbee!

This is what the filenames of the introduction package might be:

- introductionpackage-4.5.0.zip

- introductionpackage-4.5.0.tar.gz


.. blank-package:

Blank Package
~~~~~~~~~~~~~

The blank package is the TYPO3 source and a skeleton site. It is the
same as source and dummy together.


.. _typo3-source:

TYPO3 Source
~~~~~~~~~~~~

This contains only the source files of TYPO3 CMS. They are mandatory in
all TYPO3 systems. If you want to set up a new website from scratch
using the source package, you will also need the dummy package. In that
case better take the blank package, instead - there you directly get
source and dummy together. The files and folders, which are part of the
source package, remain unchanged when you run TYPO3. When you do an
update, these files and folders must be replaced.


.. _typo3-dummy:

TYPO3 Dummy
~~~~~~~~~~~

This is a skeleton for a new TYPO3 website. The contents of these
folders are modified when you run TYPO3. They will later contain the
files which are in that way only needed in *your* installation, e.g.
configuration files and images or documents which you present the
visitors of your website.


.. _recommendation:

Recommendation
~~~~~~~~~~~~~~

For testing and learning we recommend you to use the introduction
package.

For building your own website from scratch, use the blank package. In
contrast to using the introduction package, you will get a completely
empty installation of TYPO3 then.


.. _which-file-format-to-use:

Which File Format to use
""""""""""""""""""""""""

Each package is normally available as a .zip or .tar.gz distribution.
The main difference is that the .tar.gz distribution contains
symlinks: The .tar.gz distribution of the dummy package contains
symlinks to link to the source package.

If you use a Windows server, you should use the .zip distribution,
because symlinks are not easy to use on Windows.

If you run TYPO3 on a Unix server, you can use both packages. Using
the .tar.gz distribution with symlinks generally is recommended, as it
e.g. makes updating easier. Use this only if you know how symlinks
work.

