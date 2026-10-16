# repository

Public Maven repository for sopranoworks / rusty-raven artifacts, served by GitHub Pages.

```
https://sopranoworks.github.io/repository/
```

No authentication is required.

## sbt

```scala
resolvers += "sopranoworks" at "https://sopranoworks.github.io/repository/"
```

## Maven

```xml
<repositories>
  <repository>
    <id>sopranoworks</id>
    <url>https://sopranoworks.github.io/repository/</url>
  </repository>
</repositories>
```

## Gradle

```groovy
repositories {
    maven { url "https://sopranoworks.github.io/repository/" }
}
```
