Changes by Version
==================
Release Notes.

8.15.0
------------------

* Enhance lettuce plugin to adopt uniform tags.
* Expose complete Tracing APIs in the tracing toolkit.
* Add plugin to trace Spring 6 and Resttemplate 6.
* Move the baseline to JDK 17 for development, the runtime baseline is still Java 8 compatible.
* Remove Powermock entirely from the test cases.
* Fix H2 instrumentation point
* Refactor pipeline in jedis-plugin.
* Enhance kotlin coroutine plugin for stack tracing.

#### Documentation
* Update docs of Tracing APIs, reorganize the API docs into six parts.
* Correct missing package name in native manual API docs.
* Add a FAQ doc about "How to make SkyWalking agent works in `OSGI` environment?"

All issues and pull requests are [here](https://github.com/apache/skywalking/milestone/168?closed=1)

------------------
Find change logs of all versions [here](changes).
