# meilix-artwork

[![Join the chat at https://gitter.im/fossasia/meilix](https://badges.gitter.im/fossasia/meilix.svg)](https://gitter.im/fossasia/meilix?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/fossasia/meilix.svg?branch=master)](https://travis-ci.org/fossasia/meilix-artwork)

The goal was to move the plymouth theme package debuilding from the meilix repository (https://github.com/fossasia/meilix) to this independent one. meilix-artwork comprises the sources for the two plymouth bootscreen theme packages for Meilix.
- plymouth-meilix-logo_1.0-1_all.deb 
- plymouth-meilix-text_1.0-1_all.deb

TODO: Add Screenshots see ticket #20

The naming meilix-artwork follows the convention on Debian family distributions, see xubuntu-artwork etc.

We use Travis (https://travis-ci.org/fossasia/meilix-artwork) for debuilding the two debian packages, one for logo, one for text based startup screen. At present these files are found in the deb branch of this repository.

These two packages should be installable/testable on any Debian or Ubuntu derivate system and could be configured as the default boot screen.

TODO: howto install and test see issue #16

See https://wiki.ubuntuusers.de/Plymouth/ for details.

