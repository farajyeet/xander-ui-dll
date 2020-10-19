# xander-ui-dll

```
$ dotnet nuget add source https://nuget.pkg.github.com/faraaj/index.json -n github -u faraaj -p GH_TOKEN [--store-password-in-clear-text]
// Step 2: Pack
$ dotnet pack --configuration Release
// Step 3: Publish
$ dotnet nuget push "bin/Release/xander-ui-dll.1.0.0.nupkg" --source "github"
```
