Macroing JavaFX
===============
Macroing JavaFX is an extension to the standard JavaFX library.

Getting Started
---------------
To clone this repository and build the project using Apache Ant, you can type the following in Git Bash.

```bash
git clone https://github.com/macroing/JavaFX.git
cd JavaFX
ant
```

Supported Features
------------------
 - `org.macroing.javafx.concurrent` provides an extension to `javafx.concurrent`.
 - `org.macroing.javafx.scene.control` provides an extension to `javafx.scene.control`.
 - `org.macroing.javafx.scene.image` provides an extension to `javafx.scene.image`.
 - `org.macroing.javafx.scene.layout` provides an extension to `javafx.scene.layout`.

Documentation
-------------
The documentation for this library can be found in the Javadocs that are generated when building it.

Library
-------
The following table describes the different APIs and their current status in the library.

| Name                              | Javadoc | Unit Test | Package                           |
| --------------------------------- | ------- | --------- | --------------------------------- |
| Macroing JavaFX Concurrent API    | 100.0%  |   0.0%    | org.macroing.javafx.concurrent    |
| Macroing JavaFX Scene Control API | 100.0%  |   0.0%    | org.macroing.javafx.scene.control |
| Macroing JavaFX Scene Image API   | 100.0%  | 100.0%    | org.macroing.javafx.scene.image   |
| Macroing JavaFX Scene Layout API  | 100.0%  |   0.0%    | org.macroing.javafx.scene.layout  |

Dependencies
------------
 - [Java 8 - 17](http://www.java.com).

Note
----
This library has not reached version 1.0.0 and been released to the public yet. Therefore, you can expect that backward incompatible changes are likely to occur between commits. When this library reaches version 1.0.0, it will be tagged and available on the "releases" page. At that point, backward incompatible changes should only occur when a new major release is made.