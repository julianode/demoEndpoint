# singleEndpoint
Single endpoint demo application - RESTful architeture.

Just for studying purposes.


## How to use it (with gradle)

Clone the repository or download and unzip it.

Open the command-line prompt inside the project folder.

Use the command "gradle assemble", this will download dependencies and set up the code.

Use the command "gradle run".
    A Tomcat server will be running in your machine at the port 8080.
    After done, to close it, use "Ctrl + C" (the same shortcut for copying text in Microsoft Word).

With the application running:
    Open your browser and type at the address bar "localhost:8080/hello".
    This means "inside this machine, go to the appliction at the port 8080 and access the 'hello' resource".

    The browser will open a blank page with one line of text, "Hello World!".

    If you try again with a parameter such as your name, then it will display "Hello, YourName!".
    Type at the address bar "localhost:8080/hello?name=YourName".
    The character "?" indicates that a parameter is after it.
    The browser recognizes it as the name parameter and matches the application name parameter with its content.
    Finally, the browser receives the response and renders it.

