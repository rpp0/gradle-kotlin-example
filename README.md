Building a fat JAR artifact
---------------------------

1. Click ```File > Project``` Structure
2. Press the green plus and select *Other*
3. Type the name of the artifact in the top input field
4. Click ```<output root>``` and select the ```Create Archive``` icon
5. Name the archive and select it
6. Press the ```Choose existing Manifest``` button and select the ```MANIFEST.mf``` file in ```src/resources/META-INF```
7. Open the top HelloWorld element in the right pane
8. Select all ```org.jetbrains libraries``` and then right click and select ```Extract into Output Root```
9. Double click ```HelloWorld_main``` compile output
10. In the left pane, drag all list entries into your JAR file
11. Final result should look like this:
12. Go to ```Build > Build Artifacts``` to build the artifact.
13. Inside the ```out/artifacts/hello_world``` folder, execute ```java -jar hello-world.jar```
