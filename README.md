# AspNetCoreTemplate
A basic ASP.NET Core template to use with dotnet CLI.


## How to install it

In order to install this template in your computer, you must have installed [.NET Core](https://github.com/dotnet/core). If you want to check your dotnet core installation, open a terminal and run:

    dotnet --version

Next, clone this repo:

    git clone https://github.com/fcartu/AspNetCoreTemplate.git

And run this command:

**Be aware to change the path of the project for your own path.**

    dotnet new --install /Users/fcartu/github/AspNetCoreTemplate/Template


After installed you will see the new template in your template list.

![list of installed templates](.github/dotnet-template.png)

## Uninstall

The current version of DotNet CLI does not support an uninstall command, so you must reset your templates back to the default list

**_Warning:_ this command will set back your dotnet new list to "factory defaults".**

    dotnet new --debug:reinit