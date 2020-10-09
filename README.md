Scripted local dev startup for dfc-coursedirectory microservices

- https://github.com/SkillsFundingAgency/dfc-coursedirectory etc

## Get running

You'll need

* https://asdf-vm.com/ - to install the build/run dependencies of this and the other repos
	* https://github.com/asdf-vm/asdf-ruby
	* https://github.com/emersonsoares/asdf-dotnet-core
* https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local for the function apps

```
asdf install
bundle
./up
```

## See also

* https://github.com/tmuxinator/tmuxinator can fire up all the processes for you
