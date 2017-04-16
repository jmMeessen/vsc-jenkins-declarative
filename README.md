# vsc-jenkins-declarative README


This is the README of the Visual Studio Code (VSC) Declarative Jenkinsfile Syntax Highlighter add-on. 

> With version 2 of the Jenkins Continuous Integration/Continuous Delivery (CI/CD) server, a new job definition file has been introduced, called Jenkinsfile. The initial Jenkinsfile format was based on Groovy. As groovy knowledge is not that widespread, a new and more straight forward was published in spring 2017. This format is called Declarative Pipeline. This add-on is aimed at making the manipulation of this file type easier.

A description of the format can be found on [https://jenkins.io/doc/book/pipeline/syntax/index.html](https://jenkins.io/doc/book/pipeline/syntax/index.html).

## Features

The add-on will highligh the key elements of a Declarative Jenkins Pipeline. The elements of **section** (like *post*, *stages* or *step*) and **directive** (like *agent*, *environment* or *tools*) level are colorized. The **script** element (that contains Groovy code) are not specifically parsed. 


## Installing

### Method 1 (development)

* Clone the repository. 
* Open the `package.json` file in VSC 
* Press F5 to start the debug version of the module. 
* Either create a new file or open one of the files stored in `./test` to test the highlighter. 

### Method 2

to be described

## Known Issues

Under test.

If the correct file type is not detected at opening, it can be selected with the language selector at the bottom right of the editor's screen.

## Release Notes

### 0.1.0

Initial release 

## Licence

**MIT License**

Copyright (c) 2017 Jean-Marc MEESSEN <jean-marc@meessen-web.org>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.