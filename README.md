# Git Submodules

This is the top project.

I have already made commits and added a remote.

I am already tracking `foo/`.

Can I make it a submodule?

```sh
git submodule add ./foo
'foo' already exists in the index
```


Follow these steps to split a directory into a new project.
  https://help.github.com/en/articles/splitting-a-subfolder-out-into-a-new-repository


Remove foo/, commit.
git submodule add git@github.com:reergymerej/super-doodle-foo.git foo
