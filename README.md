# Godot Dependency Graph creator

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/sikkiv/godot-dependency-graph/badge)](https://securityscorecards.dev/viewer/?uri=github.com/sikkiv/godot-dependency-graph)

This is a tool to create a dependency graph in order to show proper separation of your code and also the complexity of it.

## TODOs

- [ ] check how to provide a simple way to scan all the files for their dependencies
  - [ ] scan .tscn files for \[gd_scene...\] and \[ext_resource...\]
  - [ ] scan .gd files for "signal" and "connect()" and "var" + "get_node" (or equivalents like "$someNode") and "var" + "preload"
  - [ ] how to check for things like "GameVariables" which is a global autoload?! -> can be read from .godot file!
  - [ ] do we also need to check for "class_name" in .gd files?!
- [ ] which visualization program / format should we use to express our graphs?
