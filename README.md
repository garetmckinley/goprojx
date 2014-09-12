# goprojx
## Manage Go Projects with ease

## Todo
- Create a mkgoprojx function for creating projects
  1. Initialize an empty dir in the $GOPROJX directory
  2. Return an error if project already exists
  3. After dir is initialized, set current dir to project
- Create a rmgoprojx function for removing projects
  1. Remove a project dir in the $GOPROJX directory
  2. Present the user with a confirmation message before delete if the dir is not empty
  3. Return an error if dir doesn't exist
  4. Add an autocomplete script, autocompleting project names
- Create a projx function for navigating to projects ✓ (Done for now)
  1. Return an error if project doesn't exist ✓
  2. Add an autocomplete script, autocompleting project names ✓

## License
goprojx is licensed under the BSD license

## Credits
[Garet McKinley](http://igaret.com) (@iGARET on GitHub and Twitter)
