Test Driven Development Project
===
<br>

Synopsis
---
The goal of this **[Udacity](https://www.udacity.com/)** project is to become familiar with the **[Jasmine](http://jasmine.github.io/)** development framework by applying it to a pre-existing application. It also introduces the concept of "test driven development" where test suites are created first, then the application is coded until it no longer fails the tests. Following this approach ensures that future function additions to the application do not break existing features.

The test source code is located in _jasmine/spec/feedreader.js_

_Udacity Description_
In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included Jasmine and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


Link
---
Access the test page **[here](http://genkibit.github.io/udacity-fend-test-driven-development/)**.


Suggested Test Suites
---
The application lacks a function to handle errors generated by either the absence of feed data or from server requests.
An error notification feature would help improve the application's usability.

There are three tests added that check for this. The first checks that the error node is displayed when an error is generated. The remaining two suites check for the feed data and request errors respectively. Note that these will always fail if the application successfully loads the feeds. The feed data error message should appear if the <code>allFeeds</code> variable is set to <code>undefined</code> or an empty array. There are many possible server request errors from the Feed API's <code>result.error.code</code> object, but for the last test, we check for a bad request specifically. Messing up the urls should trigger the 400 error code.


License
---
Read LICENSE.txt file.