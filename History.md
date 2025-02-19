# History

## 1.0.0 / 2015-11-06
* In this version we updated to a lot of features of JadeJs 1.11 (2015-06-12).
* Breaking Change: Instead of 'id = 5' you must use '- var id = 5'
* Breaking Change: Instead of 'h1(attributes, class = "test")' you must use 'h1(class= "test")&attributes(attributes)'
* Breaking Change: Instead of '!!! 5' you must use 'doctype html'
* Breaking Change: Instead of '!!! 5' you must use 'doctype html'
* Jade Syntax for Conditional Comments is not supported anymore
* Thanks to rzara for contributing to issue-108

## 0.4.3 / 2015-05-27
* Accepted pull request from dusanmsk (#91) regarding mixin argument splitting and added further tests.

## 0.4.2 / 2015-03-18
* added issue89: Test files renamed (was #89 instead of #90).

## 0.4.1 / 2014-11-29
* fixed tab support #79
* .jade file extension appending is now done before the template loader #71
* added support for mixin default blocks #80

## 0.4.0 / 2013-11-20
* we are now on maven central #25
* adapted pom to meet sonatype requirements
* changed artifact group id
* fixed double output of objects implementing Map and Iterable interfaces #63

## 0.3.17 / 2013-10-09
* added sources to maven repository
* added support for multiple block statements in one mixin
* fixed issues when using if/case statements inside a mixin

## 0.3.16 / 2013-10-07
* allowed including files without having to register a specific filter
* enabled self closing tags with trailing "/" #57

## 0.3.15 / 2013-09-12
* added support for including non jade files (js, css, ...) inside a template

## 0.3.14 / 2013-08-24
* added ability to clear expression and template caches
* added new convenience method to Jade4J thats lets you use Reader #49

## 0.3.13 / 2013-08-21
* the indentation exception shows the expected indent sequence #50
* code nodes can have sub blocks #44
* better error message for invalid attribute definition #37
* blockquotes are now parsed correctly and don't interfere with "layout blocks" #45
* ExpressionStrings are now evaluated multiple times to support expressions that point to expressions #47

## 0.3.12 / 2013-06-20
* reduced jexl log level for 'unknown variable' messages
