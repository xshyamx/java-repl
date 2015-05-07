# Java REPL

Java REPL is a simple Read-Eval-Print-Loop for Java language.

* Support for most of Java language constructs
* Access from console as well as web terminal via browser
* Create imports, methods, classes, enums and interfaces
* Load classes from any jar file or directory (including web urls)
* Load and evaluate expression from file
* List previous results, imports, created types and methods
* Show history of evaluations
* Search and evaluate expression from history
* Clear and replay previous evaluations
* Load and evaluate any Java source file
* Basic code completion for results, classes and methods
* Coloured output for console and web terminal

Web version is available at [www.javarepl.com](http://www.javarepl.com/).


## Build

[![Build Status](https://travis-ci.org/albertlatacz/java-repl.png?branch=master)](https://travis-ci.org/albertlatacz/java-repl)

Building Java REPL requires the [maven](http://maven.apache.org/).

After cloning the git repository, navigate over to it and run:

```
$ mvn package
```

After this completes, the jar completed with bundled dependencies will be located at **target/javarepl.jar**


## Usage
To run Java REPL you need to install **Java Development Kit (JDK) 6 or newer**. Download it from [here](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and follow install instructions. Once JDK is installed and configured you can run:   


```
$ java -jar javarepl.jar
```

If this doesn't work try to run pointing directly to *java* executable within JDK, like so


```
$ <PATH_TO_JDK>/bin/java -jar javarepl.jar
```


## Donations
If you like JavaREPL you can tip it via [Gittip](https://www.gittip.com/albertlatacz/)

Donating small amount will help to move the service onto more powerful EC2 machine, which provides faster execution
and allows more users.


## License

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
