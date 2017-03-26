# C++ Boilerplate
[![Build Status](https://travis-ci.org/dpiet/cpp-boilerplate.svg?branch=master)](https://travis-ci.org/dpiet/cpp-boilerplate)
[![Coverage Status](https://coveralls.io/repos/github/dpiet/cpp-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/dpiet/cpp-boilerplate?branch=master)
---

## Overview
Test
Simple starter C++ project with:

- cmake
- googletest

## Eclipse Integration
- cd into your project directory
- cmake -G "Eclipse CDT4 - Unix Makefiles" 

The last step will create the neccesary .project files to import your project into eclipse.
Within Eclipse

- File->Import->Existing Project into Workspace
- Projct -> Build all

- Source Material ( https://www.johnlamp.net/cmake-tutorial-2-ide-integration.html )

## CPPCheck Integration
- Help -> Eclipse Marketplace
- search for  ( cppcheclipse )  and  select install.
- accept license 
- restart eclipse 

on the command line enter
- which cppcheck
- note the path of ccpcheck

within eclipse 
- windows -> prefernces -> c++ -> cppcheck
- enter the path in the previous step
- Enter  and restart eclipse 
- cppcheck --> Run cppcheck by right clicking on your project.


## Google C++ Style Integration 
 Download the xml that will be imported from eclipse by performing a wget
- wget https://raw.githubusercontent.com/google/styleguide/gh-pages/eclipse-cpp-google-style.xml

Import the XML file  into Eclipse 
- Window -> Preferences -> C/C++ -> Code Style -> Formatter -> import  
- Select Ok






## Installation

- Checkout the repo (and submodules)
```
$ git clone --recursive https://github.com/dpiet/cpp-boilerplate.git
```

