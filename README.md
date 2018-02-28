# Minna Utilities

This library provides various helpful utilities for when working with Scala code.

## Setup

Add the following to your `build.sbt` file:
```scala
libraryDependencies += "tech.minna" %% "utilities" % "1.0.0"
resolvers += Resolver.bintrayRepo("minna-technologies", "maven")
```

This library is compiled for both Scala 2.11 and 2.12.

## Documentation

### PathAsString.pathAsString

Converts a access path to a string.

```scala
PathAsString.pathAsString((f: Family) => f.mother.name.last) => "mother.name.last"
```