---
layout: default
title: Scala
parent: Installing AIDDL
nav_order: 3
grand_parent: Getting Started
---

First, install the [Scala Build Tool
(SBT)](https://www.scala-sbt.org/download.html).

We use `<AIDDL>` as the root of the [aiddl.org](http://www.aiddl.org) git
repository. To install the AIDDL libraries, open a console in the root of the
library you would like to install:

1. Core library: `<AIDDL>/core/scala/`
2. Util library: `<AIDDL>/util/scala/`
3. Common library: `<AIDDL>/common/scala/`

For each of these (in the listed order) open sbt:

        sbt
        
Once sbt has started, run the following in the sbt console:

        compile; test; publishM2
        
This will compile the project, run all test cases, and finally publish the project in your local Maven repository. 
    

