# Mainzelliste.Client

## General information
Mainzelliste (see <http://www.mainzelliste.de>) is a web-based patient list and pseudonymization service. It provides a RESTful interface for client applications like electronic data capture (EDC) systems. 

Mainzelliste-Client handles the HTTP calls necessary for using Mainzelliste from a Java application. It has been released as part of the Open Source Registry System for Rare Diseases in the EU (see <http://osse-register.de>).

## Release notes

This section moved to [changelog.md](./Changelog.md)

## Build

Use maven to build the jar:

``` 
mvn clean package
```

Use it as a dependency:

```xml
<dependency>
	<groupId>de.pseudonymisierung</groupId>
	<artifactId>mainzelliste-client</artifactId>
	<version>1.1.0</version>
</dependency>
```

## Copyright and License
Mainzelliste-Client has been released as part of OSSE and is thus licensed under the same conditions:


```
#!text
Copyright (C) 2015 Working Group on Joint Research,
Division of Medical Informatics,
Institute of Medical Biometrics, Epidemiology and Informatics,
University Medical Center of the Johannes Gutenberg University Mainz

Contact: info@osse-register.de

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU Affero General Public License as published by the Free 
Software Foundation; either version 3 of the License, or (at your option) any
later version.

This program is distributed in the hope that it will be useful, but WITHOUT 
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS 
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more 
details.

You should have received a copy of the GNU Affero General Public License 
along with this program; if not, see <http://www.gnu.org/licenses>.

Additional permission under GNU GPL version 3 section 7:

If you modify this Program, or any covered work, by linking or combining it 
with Jersey (https://jersey.java.net) (or a modified version of that 
library), containing parts covered by the terms of the General Public 
License, version 2.0, the licensors of this Program grant you additional 
permission to convey the resulting work.
 
```
