# Java Web Application

## Setup Credentials for Remote Deployment

Create a file named `gradle.properties` and insert your credentials
for remote deployment and make sure to never commit this file!

```
user='me'
password='my-very-secret-password-123'
```

## Build the Web Archive

```
./gradlew war
```


## Deploy the Web Archive to a Local Tomcat

```
./gradlew deployToTomcat
```

## Deploy the Web Archive to a Remote Server

```
./gradlew deploy
```