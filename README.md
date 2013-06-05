gsk-to-xml-parser
=====================

A java parser to create a XML-document of the IT-Grundschutz-Katalog. The
IT-Grundschutz-Katalog is orginally published by the BSI on
https://www.bsi.bund.de/DE/Themen/ITGrundschutz/ITGrundschutzKataloge/itgrundschutzkataloge_node.html.

The created XML-Document is defined in the XML-Schema gsk.xsd.

Usage:
 1. compile a JAR-File with ant dist
 2. run parser with 'java -cp dist/WebParser.jar:lib/jsoup-1.6.3.jar
 de.ipm.gsk.WebParser' to generate the XML-File gsk.xml.