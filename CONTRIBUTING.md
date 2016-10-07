# Development tips

## Fetching all dependencies using NuGet on the CLI
If you should be so masochistically inclined that command line tools
is your thing, you can issue the following command from the root 
to fetch all needed dependencies:
```
nuget restore \
    -Source 'http://nuget.episerver.com/feed/packages.svc' \
    -Source 'https://api.nuget.org/v3/index.json'
```

## Working with Mono
If you have fetched all dependencies using NuGet you can proceed to 
build the solution simply by issuing `xbuild`.
