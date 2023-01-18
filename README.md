# mind

- "Mind is not about the content, it is a way to structure it. Link, etc.."

- A global tree is a tree that is unique to your machine / computer. Opening your main Mind tree from Neovim will always open and edit that tree. It’s basically your central place for your Mind nodes.

- A local tree is a tree that is relative to a given directory. Mind implements a cwd-based local form of tree, so you can even share those trees with other people (as long as they use Mind as well).

- Atop of that, Mind has the concept of “project” trees, which are either global or local.

    - A global project tree is stored at the same place as your main tree and the purpose of such a tree is to be opened only when your `cwd` is the same as the tree, but you don’t want the tree to be in the actual `cwd` - that can be the case if you work on a project where you don’t want to check the tree in Git or any versioning system.

    - A local project tree is what it means: it lives in the `cwd`, under `.mind`, basically.
