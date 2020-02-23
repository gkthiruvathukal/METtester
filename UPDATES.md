The code can now be compiled with Gradle.
This makes it easy to maintain the code in the future.

To build the METTester tool:

```
gradlew compileJava jar
```

On Unix, you may have to do:
```
./gradlew compileJava jar
```

On Windows, you may have to do:

```
.\gradlew compileJava jar
```

This will result in an executable fat jar in `build/libs`

```
java -jar build/libs/METtester-1.0.jar
```

More to come. But it works! :)
