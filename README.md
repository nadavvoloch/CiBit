# CiBit
# Operating Instructions:
Install MySQL:

During installation, choose the "Developer" configuration.
Download MySQL
Install Python 3.7 and the following libraries:

Scholarly
Logging
Hashlib
Requests
Contextlib
Warnings
Download Python
Install Scholarly
Install Logging
Install Hashlib
Install Requests
Install Contextlib
Install Warnings
Install Visual Studio:

Install ASP.net Core 2.1
Download Visual Studio
Setup MySQL:

Open MySQL Workbench and navigate to "Administration" and then "Data Import" as shown in the image below.
Select the file that came with the package and perform an import.
Configure access to the bankDb database, setting up a user who can connect and perform insert, update, execute, and delete operations.
Configure access to the cibitDB database, setting up a user who can connect and perform insert and update operations.
Provide the username and connection settings for bankDb in the connect function in the Python file Chain.py.
Provide the username and connection settings for cibitDB in the connect function in the Python file Bot.py.
Configure and Run the Server Project:

Navigate to the server project called CiBitServer.
In the controllers for transactions and users, update the variable pyFullPath to point to the Python file itself.
In the class runPythonBot, update the start.FileName initialization in both functions to the location of the bot.py file.
Update the connection strings to connect to the cibitDB database.
Select cibitServer and run it without debugging.
After that, select the webapplication and run it to view the websites.
Verify Operations:

You should see that operations performed on the site are saved in the database and also trigger the corresponding Python files accordingly.
