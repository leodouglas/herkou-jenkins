# Only listen on http; disable ajp and https
web: java -jar jenkins.war --argumentsRealm.passwd.user=password --argumentsRealm.roles.user=admin --httpPort=$PORT --ajp13Port=-1 --httpsPort=-1
