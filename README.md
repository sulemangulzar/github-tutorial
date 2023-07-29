# GitHub Tutorial

### Create a repository

- Go to [GitHub.com](https://github.com)
- Click on the `+` button
- Click on `New repository`
- Write a `Repository name`
- Click on `Create repository`

### Clone a repository
In a terminal, write `cd` to go to the root directory:

```
cd
```

Then go to `Documents/GitHub/sulemangulzar`
```
cd Documents/GitHub/sulemangulzar
```

Clone the repository:
```
gh repo clone sulemangulzar/<repo_name>
```

Go into the repo directory:
```
cd <repo_name>
```

Open in VSCode:
```
code .
```

### Commit changes and push
Stage all changes:
```
git add .
```

Commit all changes:
```
git commit -m "Message"
```

Push:
```
git push
```
