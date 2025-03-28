Install dependencies

mvn install:install-file \
   -Dfile=~/dictzip-lib-0.8.2.jar \
   -DgroupId=org.dict.zip \
   -DartifactId=dictzip-lib \
   -Dversion=0.8.2 \
   -Dpackaging=jar \
   -DgeneratePom=true

Build and publish to local repository

./gradlew build publishToMavenLocal

OmegaT is a computer-assisted translation (CAT) tool.

* [General information](release/readme.txt)
* [For developers](docs_devel/README.txt)
