# my-app 
###maven command to create a java project
'''
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-webapp -DarchetypeVersion=1.4 -DinteractiveMode=false

'''
<distributionManagement>
		 <snapshotRepository>
		    <id>nexusRepo</id>
		    <url>http://13.58.96.231:8081/repository/my-app-snapshot/</url>
		 </snapshotRepository>
		
		<repository>
		    <id>nexusRepo</id>
		    <url>http://13.58.96.231:8081/repository/my-app-release/</url>
		</repository>
  	</distributionManagement>
