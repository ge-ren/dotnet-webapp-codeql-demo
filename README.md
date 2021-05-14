# dotnet-webapp-codeql-demo
Created a simple dotnet webapp using command "dotnet new webapp" and pushed it to GitHub

From the repository's Action tab added a default workflow dotnet.yml. The workflow includes steps:
1. dotnet restore
2. dotnet build
3. dotnet test

From Security tab selected 'Code scanning alerts' and added 'CodeQL Analysis' workflow 

