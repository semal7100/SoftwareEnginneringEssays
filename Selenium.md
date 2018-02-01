# Overview of Selenium Framework

## Introduction

In an era of highly interactive and responsive software processes where many organizations are using some form of Agile methodology to improve their productivity and compete with the software and processes of the other organizations, test automation is frequently becoming an essential requirement for software projects. Testing is slowly becoming as paramount a process as software development and is sometimes run concurrently with the software development to make sure that the software satisfies the requirements at every stage of production.Test automation refers to using a software tool such as Selenium or SoapUI to run repeatable tests against the application to be tested.


Selenium is a software-testing framework used mainly for web applications.Selenium provides a tool for authoring tests without the need to learn a test scripting language and it makes use of Selenium IDE to achieve it. One can also make use of Selenese to write tests in a number of programming languages that we make use of in our daily life such as C#,Java, PHP, Python or Scala. Selenium can be also thought of as a set of different software tools each with a different approach to support test automation and thereby ease the process of software testing.


Even though the basic functionality of Selenium is to test web applications, but it can still perform many different tasks.It can be used to automate boring web based administration tasks. Selenium is the core technology in many browser automation tools,frameworks and APIs around the world.


![Execution of a Recorded Script in Selenium using Internet Explorer](http://software-testing.wdfiles.com/local--files/introduction-to-selenium/selenium_test_runner.JPG)


## History

Selenium was originally developed by Jason Huggins in 2004 when he was testing an internal application at ThoughtWorks.He developed a Javascript library that intearcted with the page, which allowed him to rerun tests against multiple browsers at that time automatically. That library eventually became one of the essential component of Selenium known as Selenium Core, which underlied all the functionality of Selenium Remote Control (RC) and Selenium IDE. Selenium Remote Control was outstanding as no other product at that time allowed you to control a browser from a language of your choice. All these constituents of Selenium made it useful to easily test web applications.


## Components
Selenium is composed of several components with each performing a specific role while developing web applications:<br>



* **Selenium IDE:** 
Selenium IDE,previously known as Selenium Recorder, is a complete integrated development environment (IDE) for Selenium tests. It is implemented as a Firefox Add-On, and allows a tester or Quality Assurance Engineer to record, edit, and debug tests. 


* **Selenium Remote Control:** Selenium Remote Control (RC) is a server, written completely in Java, that accepts commands for the browser and uses HTTP to achieve that. RC makes it possible to write automated tests for a web application in any programming language, which allows for better integration of Selenium in existing unit test frameworks. To make writing tests easier, Selenium project currently provides client drivers for PHP, Python, Perl and Java. The Java driver can also be used with JavaScript using the Rhino engine. An instance of selenium RC server is needed to launch html test case. This means that the port should be different for each parallel run.



* **Selenium WebDriver:** Selenium WebDriver is the successor to Selenium RC. Selenium WebDriver accepts commands ,which can be sent in Selenese or a Client API, and sends them to a browser. This is implemented through a browser-specific browser driver, which sends commands to a browser, and retrieves results. Most browser drivers launch and access a browser application such as Firefox, Chrome or Internet Explorer; there is additionally an HtmlUnit browser driver, which simulates a browser using HtmlUnit.


* **Selenium Grid:** Selenium Grid is a server that allows tests to make use of web browser instances running on remote machines. With Selenium Grid, one server performs the role of the hub.Tests contact the hub to obtain access to browser instances. The hub has a list of servers that provide access to browser instances such as WebDriver nodes, and allows tests use these instances. Selenium Grid also allows to run tests in parallel on multiple machines, and to manage different browser versions and browser configurations centrally.


## Conclusion

Hence we can observe that using an automated test tool such as Selenium and the different components that it offers, one can ease the process of software testing and build software applications that are not only durable but of high quality also. There are many other automation tools for web applications, but Selenium provides an ease of use to the tester as well as tests software applications rigorously. Hence it is one of the most popular tools among testers and used widely by many organizations in the process of software development.



---
References: 
1. https://en.wikipedia.org/wiki/Selenium_(software)
2. http://www.seleniumhq.org/
3. http://software-testing.wikidot.com/introduction-to-selenium


---

Author :Shemal Somil Lalaji (shla8652@colorado.edu)
