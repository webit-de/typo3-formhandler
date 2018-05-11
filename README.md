TYPO3 Formhandler - Patch Version
=================================

:collision: The original [formhandler TYPO3 extension](https://github.com/reinhardfuehricht/typo3-formhandler)
is no longer maintained. This is a fork, with custom patches. Feel free to 
add your own and send a pull request. We don't take over maintenance however,
any support tickets will be closed.

Usage
-----

Installation with Composer

    composer config repositories.formhandler-patch-version vcs https://github.com/webit-de/typo3-formhandler.git
    composer require typoheads/formhandler 

All patches are merged into ```master``` and tagged with a [new release number](https://github.com/webit-de/typo3-formhandler/tags).

:information_source: The last official release of formhandler was version [2.4.0](https://github.com/reinhardfuehricht/typo3-formhandler/tags). 

Suggestions
-----------

* Require this fork in your legacy projects which depend on `EXT:formhandler`
* Add [EXT:formhandler_clearlog_task](https://packagist.org/packages/webit-de/formhandler-clearlog-task)
  as requirement to delete formhandler logs periodically
* :arrow_upper_right: Migrate existing formhandler forms to the core extension [EXT:form](https://packagist.org/packages/typo3/cms-form)
