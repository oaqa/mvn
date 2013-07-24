mvn
===

This repository contains the aggregate of all Maven artifacts (parent POMs and project archetypes) used in OAQA projects.

## Layout

This repository, like others in the OAQA, contains mulitple projects.  Each project has it's own folder, though all of them are tracked under the same repository for reasons of organization and convenience.

## Projects

### oaqa-archetype

This is the project for the default archetype for all OAQA projects.  An archetype generally defines the directory layout of a Maven project, along with some other meta-attributes, and a template POM for the project.  This archetype is no different.  It is designed to be as minimal as possible, and to keep all OAQA Maven projects consistent in their general feel.

* Data Storage: none
* Protocols: none
* Architecture: Maven archetype
  The two main files of concern are: resources/archetype-resources/pom.xml (the POM template) and resources/META-INF/maven/archetype.xml (meta information descriptor).
  Specifically, this project is specially packaged by Maven to be an archetype, i.e. it is not packaged as a jar, etc.
* Code Conventions: generic XML and POM conventions
* Project Style: nothing special
