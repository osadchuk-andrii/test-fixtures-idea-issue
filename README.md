## IntelliJ IDEA Issue Resolving Test Fixtures

IntelliJ IDEA cannot resolve test fixtures for the app project from the lib project when using:

`testImplementation(testFixtures("com.example:lib:1.0-SNAPSHOT"))`

if the `lib` project is located in the same workspace.

## Building the Projects

### `lib` project:

`cd lib`

`gradle build publishToMavenLocal`

### `app` project:

`cd app`

`gradle build`


