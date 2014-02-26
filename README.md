solr-jetty-console
==================

Maven project for generating a jetty-console-war for Solr

To generate a jetty-console-war, a war with jetty embedded, run
mvn clean install -Dsolr.version=VERSION and the created file will end up as target/jetty-solr-VERSION-jetty-console.war.
VERSION in this command is the version of Solr to use.