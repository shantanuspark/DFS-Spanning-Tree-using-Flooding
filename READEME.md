This program creates a DFS Spanning tree using flooding algorithm.
I have used a static graph, but the program can handle any graph. In the main.java class, I have an init() method which creates the graph. You can use any graph as required.
Below is the graph I have used:
<img src="https://github.com/shantanuspark/DFS-Spanning-Tree-using-Flooding/blob/master/input.JPG" />

You have several options for running it...

---- RUN IN AN IDE ----

If you want to run the examples in an IDE, such as Eclipse, you should be able to import the entire the project as an existing project.
Once the import is successfull, go to run configuration and set a program argument(integer between 0-5) which defines the node to be used as root.


---- COMPILE AND RUN ON THE COMMAND LINE ----

To compile the program, navigate to the "DC_HW01\src\edu\dt" directory in the terminal or command prompt.
Run the command 

				javac *.java
				
This will compile the program and generate the class files.
Now, Navigate back to the src directory "DC_HW01\src" and run the command

				java java edu.dt.Main 0
				
Remeber to enter the command line argument, it is an integer between 0-5, which defines the node to be used as root.
