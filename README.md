## Space Invaders Game

Code from the java 2d tutorial at [cokeandcode](http://www.cokeandcode.com/info/tut2d.html).
Copied here with permission from author.

## With Gradle

### Build with gradle
`gradle jar`

### Run with gradle
`gradle run`
OR, after "Build with gradle"
`java -jar build/libs/*.jar`

## Vanilla Java

### Build with Vanilla Java
`javac -d build/classes/main/ src/main/java/org/newdawn/spaceinvaders/*.java`

### Run with Vanilla Java
`java -cp build/classes/main/:src/main/resources org.newdawn.spaceinvaders.Game`
