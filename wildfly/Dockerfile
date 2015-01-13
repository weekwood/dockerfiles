FROM jboss/wildfly

ADD javassist-module.xml /opt/jboss/wildfly/modules/system/layers/base/javassist/javassist/main/module.xml
ADD javassist.jar /opt/jboss/wildfly/modules/system/layers/base/javassist/javassist/main/javassist.jar

ADD standalone.xml /opt/jboss/wildfly/standalone/configuration/standalone.xml


EXPOSE 8080
