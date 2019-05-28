# Learn-Lessons-CleanUp

The objective for this project is to create a master repo that links to all the lessons in the curriculum.  

**A)** You want a nice `github` repo where you can quickly look through all your lessons. Who doesn't want that?

**B)** Your local file structure is a mess. You saved some stuff over here. You saved some stuff over there. Then you went in a new direction with a naming scheme.

`git` has its own idea of nested file structure. It uses _**submodules**_ to reference different repos. The following code automates the process of adding all the lessons you have done to a single `github` repo. 

A side effect of adding a `submodule` to a repo is that `git` clones that file to your local machine again, creating a set of redundant files. Once you are done with this process, the choice is yours of what files you wish to keep locally. If you are inclined to keep the the organizational structure introduced here, feel free. Otherwise, just delete the recently cloned files.