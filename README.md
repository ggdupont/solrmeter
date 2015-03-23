SolrMeter
=========

Migrated from the original (Google Code repository)[http://code.google.com/p/solrmeter/] after (Google announcement to discontinue the service)[https://github.com/m-khl/solr-meter/blob/master/sources/solrmeter/src/main/resources/solrmeter.properties].

## Installation

The following steps should be followed to compile and package SolrMeter (Maven is required)
```bash
git clone https://github.com/lafourchette/solrmeter.git
cd solrmeter/sources
mvn package

# Running the created jar
java -jar solrmeter/target/solrmeter-*-jar-with-dependencies.jar
