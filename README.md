# Git is complicated

In addition to branches, there's also tags.

List remote branches:
```
git fetch origin
git branch -r
```

List remote tags:
```
git fetch origin --tags
git tag
```

Checkout a tag:
```
git checkout <tag>
```

Technically these track locally-tracked copies of the remote information.
