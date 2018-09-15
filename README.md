# hello
.net core playground
- [hello](#hello)
    - [setup the project](#setup-the-project)
        - [1. Install the SDK](#1-install-the-sdk)
        - [2. Create the app](#2-create-the-app)
        - [3. Run the application](#3-run-the-application)
        - [4. Get an editor](#4-get-an-editor)
    - [expand the project](#expand-the-project)
        - [1. Add structure](#1-add-structure)
        - [2. Add API project](#2-add-api-project)
  
## setup the project

### 1. Install the SDK

The SDK can be found [here](https://download.microsoft.com/download/8/A/7/8A765126-50CA-4C6F-890B-19AE47961E4B/dotnet-sdk-2.1.402-osx-gs-x64.pkg)

### 2. Create the app

```sh
$ dotnet new webapi
```

### 3. Run the application

```sh
$ dotnet run
```

### 4. Get an editor

VS Code can be found [here](https://code.visualstudio.com/Download?wt.mc_id=DotNet_Home)


## expand the project

### 1. Add structure

We want to create a .net core webapi project alongside the hello console project.

dotnet projects can live next to each other, but we will introduce some structure to keep things clean: 

```sh
$ mkdir helloConsole
$ mv bin/ obj/ hello.csproj Program.cs helloConsole
```

### 2. Add API project

```sh
$ dotnet new webapi -o helloApi
```



