A lightweight version of Zend Framework 1 for use with Composer
===============================================================

This is a modified copy of the minimal release of Zend Framework 1.

## Modifications

* To improve performance with autoloaders, nearly all `require_once` calls have been commented out. Exceptions are those in Zend_Application* and Zend_Loader* classes.
