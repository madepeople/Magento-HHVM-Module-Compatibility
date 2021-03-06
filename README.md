Magento HHVM Module Compatibility
=================================

What is this?
-------------

This is a standard Magento installation that I use for testing popular module's compatibility with Magento:

  - Modules and their versions are managed through [composer](https://github.com/magento-hackathon/magento-composer-installer).
  - Modules are picked by their popularity, though due to this repository being public there will be no paid extensions. 

Please test my module too?
--------------------------

Sure:
  - Modify composer.json to add your module as a dependency.
  - Ensure that your module cleanly installs and doesn't add any rewrite conflicts.
  - Create a pull request.

How do you find the time to do this?
------------------------------------

[Byte Internet](http://www.byte.nl/) has been nice enough to provide a list of most popular repositories and are sponsoring some of my work on HHVM.
