# Dependency-Graph
This project creates a dependency graph of the source code files in a CPP project. 

It has been developed using HTML5, Javascript, Bootstrap and Java. The dependency graph is created using JavaScript and HTML5. Source code files are analyzed for dependencies at the backend using Java. 

Front End:
drawGraph.js - Draws and renders the dependency graph 

Home.html - It's the home page

Graph.html - Allows the user to upload the project and see the dependencies among the source code files


Back End:

AnalyzeCPPFiles.java - Analyzes the cpp source code files for dependencies

Constants.java - Defines the constants

Dependencies.java - Creates the xml file of dependencies

IAnalyzeFiles.java - Defines the interface for analyzing the source code files

ParseProject.java - Extracts individual files from the zip folder and puts them in the queue to be processed

Saveproject.java - The servlet that gets the HTTP request and responds to the client

