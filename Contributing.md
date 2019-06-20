# Contributing

## Github

#### Git Fork

Cette commande crée ton propre _server-side_ copy du _central_ repository. 

#### Git Clone

```bash
# clone repo
git clone username@host:/path/to/repository
```

#### Git Remote

```bash
cd <git-repo-name>
# add remote
git remote add upstream <server>
# check all remotes
git remote -v
```

#### Create bio

```bash
# Create file <name.bio> in Employees directory and write bio
echo "Lorem Ipsum" >> Employees/<name.bio>.md
```

#### Git Commit

```bash
# Stage changes
git add .
# Commit changes
git commit -m "First commit: Introduction"
```

#### Git Push

```bash
# Push changes
git push
```

#### Git Pull Request

Go back to github and create Pull Request from recent commit

#### Sync Local Repo to Central Repo

```bash
git checkout dev
git pull upstream dev
```