# Commands

### Cloning Meet the Octocat repository

![Cloning Meet the Octocat repository](./images/cloning-1.png)
![Cloning Meet the Octocat repository](./images/cloning-2.png)

```
git clone https://github.com/rossanodan/meet-the-octocat.git
```

---

### Forking a repository

What does it mean?
Why we do fork?

---

### Creating a new branch

```
git checkout -b rossanodan-uda
```

or

```
git branch rossanodan-uda
git checkout rossanodan-uda
```

![Creating a new branch](./images/vscode-1.png)

---

### Listing all branches

```
git branch
```

---

### Pushing changes

```
git add .
```

or

```
git add path/to/specific/file.txt
```

![Pushing changes](./images/vscode-2.png)
![Pushing changes](./images/vscode-3.png)

If you need to discard your changes

![Pushing changes](./images/vscode-4.png)

then

```
git commit -m "rossanodan-uda: hello, there"
```

![Pushing changes](./images/vscode-7.png)

and finally

```
git push
```

![Pushing changes](./images/vscode-8.png)

If you need to undo the last commit

![Pushing changes](./images/vscode-9.png)

If this branch doesn't exist in the remote repository, GIT will ask you to create it with a specific command

```
git push --set-upstream origin rossanoda-uda
```

or

```
git push -u origin rossanodan-uda
```

---

### Creating a pull request

![Creating a pull request](./images/pr-1.png)
![Creating a pull request](./images/pr-2.png)
![Creating a pull request](./images/pr-3.png)
![Creating a pull request](./images/pr-4.png)
![Creating a pull request](./images/pr-5.png)
![Creating a pull request](./images/pr-6.png)

---

### Commenting a pull request for code review

Or simply for a discussion that may involve more people in the team!

![Commenting a pull request for code review](./images/code-review-1.png)
![Commenting a pull request for code review](./images/code-review-2.png)

---

### Merging a pull request

![Merging a pull request](./images/merge-pr-1.png)
![Merging a pull request](./images/merge-pr-2.png)
![Merging a pull request](./images/merge-pr-3.png)

### Visual Studio Code fully integrated with GitHub

![Visual Studio Code fully integrated with GitHub](./images/vscode-10.gif)
