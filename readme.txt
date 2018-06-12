1. Import the given xml file in SOAP UI as a project
2. pass on the environment variables as required by selecting environment icon in the SOAP UI interfacefixxx i
    (i) api url
    (ii) db connection string
3. open command prompt
4. execute the below statement in the command prompt
   testrunner.bat -FPDF -R"JUnit-Style HTML Report" c:\my projects\my-project.xml -f c:\my projects
5. analyze the run based on the report generated in the folder
6. incase of failure fix the test data and then repeat steps 3,4,5

pre-requisites:
--------------
SOAP UI installed (free version also ok)
64- bit operating system
sqljdbc.jar in case of db connection needed
     