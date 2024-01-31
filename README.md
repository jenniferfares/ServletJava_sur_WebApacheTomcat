﻿# ServletJava_sur_WebApacheTomcat
Software and program downloaded:
Java Development Kit (JDK)
Web Apache Tomcat
Compile the servlet using the following command:
First Step:
javac -source 1.8 -target 1.8 -cp "TOMCAT-HOME/lib/servlet-api.jar;lib/javax.servlet-api-3.1.0.jar" MyServlet.java
Make sure the TOMCAT-HOME environment variable is set to the Tomcat installation directory.
Second Step:
Copy the compiled MyServlet.class to the Tomcat webapps/ROOT/WEB-INF/classes directory.
Third Step:
Start Tomcat.
Fourth Step:
catalina run on the CMD
Open your web browser and navigate to http://localhost:8080/MyServlet?nom=YourLastName&prenom=YourName to test the servlet.
