## Branching strategies

A walkthrough to a project ideal branching strategy.

### No branches

That is, you don't use any source control system.

Pros: it's simple.

Cons: it's too simple for any real piece of software. Probably you only want to do this when creating something with a lifespan of minutes (like a [kata](http://en.wikipedia.org/wiki/Kata_(programming)), for example).

### Master branch

It's hard to imagine a project without changes. Having a source control system with a single branch (usually called 'master' or 'trunk') allows keeping a history of the changes.

Ideally a commit should contain a single meaningful change.

Pros:

- When commit messages are meaningful, you have a nice log of the changes done.
- You can recover older versions. Think of it as a backup tool or as a super-undo.
- A corollary of previous point is that you are not that afraid of making changes.

Cons:

- You have to learn to use the source control system.
- Now you have extra steps to do as you make changes (at least creating a commit for every meaningful change)

---

### TODO

- Feature branches
- Branching by abstraction
- Single release branch
- Multiple release branches
- Versioning
- Code reviews
- Pull requests
