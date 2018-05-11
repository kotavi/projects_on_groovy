# Projects on Groovy

## Initial setup

1. Download IntelliJ for MacOS

https://www.jetbrains.com/idea/download/#section=mac

2. Install Java JDK on MacOS

http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

## How to create projects and run them in IntelliJ

3. Open IntelliJ and choose 'Create New Project'
  - on the right side choose 'Croovy'
  - on the left side setup SDK
    - if there is nothing in dropdown menu - click on New button to create new SDK
    - point to installed Java JDK
  - set up 'Groovy library' - serach it under hidden folder '.sdkman'
  (To make hidden folders visible press 'CMD + SHIFT + .')
  - The las step is to give a name to the project and provide a path

## Convert project to Maven project

1. Right-click on the current project and select "Add framework support...", and check the "Maven" technology.
As a result pom.xml file will be created


