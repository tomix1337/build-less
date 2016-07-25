"# build-less" 

This small java plugin checks any Git changes and automatically generates a command for maven to build these modules. 
-Am is included by default, this can be changed to your custom profile or commands by passing them as arguments.  
A method executeCommand is also present in the source. This was disabled because it was lagging the console and making the command less customizable. To re-enable this just un-comment the method call.

To run this tool, build the code, grab the jar file, put it next to your code and run java -jar buildless.jar.
