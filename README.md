# Builders Project

### This project consists four modules:
admin, services, utils, and web.

## Building and Testing:

### Ant+Ivy:

To build the project and create the WAR and JAR artifacts using Ant and Ivy, follow these steps:

1. Install Ant and Ivy if you haven't already.
2. Open a terminal and navigate to the project directory.
3. Run the following commands:

```bash
ant resolve    # Resolve dependencies with Ivy
ant test       # Run tests
ant build      # Build the WAR and JAR artifacts
```

### Maven:

To build the project and create artifacts using Maven, follow these steps:

 1. Install Maven if you haven't already.
 2. Open a terminal and navigate to the project directory.
 3. Run the following command:

```bash
mvn clean install
```

### Gradle

To build the project and create artifacts using Gradle, follow these steps:

1. Open a terminal and navigate to the project directory.
2. Run the following command (on Unix-like systems):

```bash
./gradlew clean build
```

On Windows, run: 

```bash
gradlew.bat clean build
```
##
### Running Tests:

To run tests separately, use the following commands:

### Ant+Ivy

```bash
ant test
```

### Maven

```bash
mvn test
```

### Gradle

```bash
./gradlew test    # Unix-like systems
gradlew.bat test  # Windows
```

##
### Enjoy building and testing!
