molindo-maven-download
======================

Simple POM to download artifacts from Maven repos

Usage
-----

```bash
mvn clean package \
  -Ddownload.group=at.molindo \
  -Ddownload.artifact=molindo-utils \
  -Ddownload.version=1.1.0 \
  -Ddownload.type=jar
```

