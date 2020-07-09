# angularwithproxysample
Sample that uses the angular dev proxy instead of our extensions

* In order to run the sample you need the latest version of .NET Core from master that can be retrieved from https://github.com/dotnet/installer
* Download the zip version (master x64) and unzip it into a folder <<extract>>.
* Set the following environment variables replacing extract and path with the appropriate values:
  ```console
  DOTNET_ROOT=<<extract>>
  DOTNET_MULTILEVEL_LOOKUP: 0
  PATH=<<extract>>;PATH
  ```
* Launch Visual Studio from the command-line using start newangular2.sln (you might need a preview version of VS).
* Set both projects as startup projects and launch the app.
