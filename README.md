# Reproduce Arquillian issues
Steps to reproduce: 
- Setup wildfly instance locally using `scripts/install_wildfly.sh`
- Run `mvn clean test -f pom.xml -Djboss.home=$JBOSS_HOME`
- Output `java.lang.NoSuchMethodError: org.xnio.XnioWorker.getContextManager()Lorg/wildfly/common/context/ContextManager;`
