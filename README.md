Release requires working around maven bug so you must use release plugin 2.5
```bash
mvn org.apache.maven.plugins:maven-release-plugin:2.5:prepare
mvn org.apache.maven.plugins:maven-release-plugin:2.5:perform -Darguments="-Dxwiki.enforcer.skip=true"
```
