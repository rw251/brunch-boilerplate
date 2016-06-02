# Boilerplate brunch setup


# Installation

- Clone the boilerplate repository
```
git clone git@github.com:rw251/brunch-boilerplate.git
```

- Install the dependencies
```
cd brunch-boilerplate && npm install
```

- Run the setup script (removes the `.git` folder and updates the `package.json` file and creates a new git repo)
```
npm run setup
```

- Assuming this is going to live in github and be deployed to gh-pages.. Push the local repo to the remote repo
```
git remote add origin git@github.com:INSERT-NEW-REPO-NAME.git
git push -u origin master
```
