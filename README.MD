1.Create a new directory for your project:

	mkdir hn369-ecommerce-db-management
	cd hn369-ecommerce-db-management
	
2. Initialize a new Maven project inside the directory:
	mvn archetype:generate -DgroupId=com.hn369.ecommerce -DartifactId=hn369-ecommerce-db-management -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
	
3. Replace the pom.xml content with the one I provided earlier.

4. Create the Java package and main class and create the main class file Hn369EcommerceDbManagementApplication.java in the new directory

	mkdir src\main\java\com\hn369\ecommerce
	
5. Create the src/main/resources/db-changelog/ directory for Liquibase