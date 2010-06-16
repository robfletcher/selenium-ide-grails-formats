# Selenium IDE: Grails Selenium RC Formatters

This is a Firefox plugin that adds formatters to [Selenium IDE][2] so that scripts can be exported as [Grails Selenium RC][1] test cases.

## Installing

The plugin's release is hosted on Selenium HQ [here][4]

## Exporting Selenium IDE tests

Once installed you should find the following menu options in Selenium IDE:

* _File -> Export Test Case As... -> Grails Selenium RC (JUnit 3)_
* _File -> Export Test Case As... -> Grails Selenium RC (JUnit 4)_

JUnit 4 tests are appropriate if you are using Grails 1.3 or above. The exported test case will not extend a base class, and will use _assertThat_ along with [Hamcrest matchers][3] rather than using _assertEquals_, etc.

[1]:http://robfletcher.github.com/grails-selenium-rc
[2]:http://seleniumhq.org/projects/ide/
[3]:http://code.google.com/p/hamcrest/
[4]:http://bit.ly/daOJpD "Selenium IDE: Grails formatters Firefox plugin installer"