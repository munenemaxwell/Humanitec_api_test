Automated postman tests  

Installation Instructions

1.Head over to https://nodejs.org/en/download/ and download the latest LTS version of Node

2.Once downloaded install node by executing the downloaded installation file

3.Add the Node executable to your system path

4.You’ll need to install the Visual Studio runtime for some Newman dependencies to be installed. The quickest way to do this is to install Visual Studio Express – http://go.microsoft.com/?linkid=9816758. To check for any additional requirements for your system, check https://github.com/TooTallNate/node-gyp (Windows).

5.Install newman globally issuing the command  “npm install -g newman” on terminal/command prompt

6.Clone the repository and navigate to it by either a terminal in mac or command prompt in windows

7.Issue the command "newman run api_tests.json" to execute the automated tests.
