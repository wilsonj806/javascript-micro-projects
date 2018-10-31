# Things Learned

This is a repository listing the various things I've learned while doing web development. Most of these are going to be small boring or basic things, but are worthwile to record somewhere. 

**Notes are liable to change as I learn more.**

## Developing on Windows

- **Git doesn't get automatically added to PATH**

## npm/ Node

- Tools should be added as dev dependencies
  ```
  npm i <package> -D
  ```
  - includes Webpack, Gulp, ESLint, etc
- Node has additional debugging options available
  - requires knowledge of Node but is worthwhile to look into since npm is built with Node
- Additional debugging can be added to `package.json` scripts by adding the following to your script:
  ```
  "scripts": {
    "start": "NODE_DEBUG=<package-name> <run-package script here>"
    //...
  },
  ```
  - got it from this article on [React directory structure](https://daveceddia.com/react-project-structure/)
  
## Git/ Github

- When pushing new features into a remote, push it to a new branch then pull request it
- Commit notes
  - commit often, keeps your changes more granular and you can track down specific thigns better
  - make sure your commit messages follow the 50/72 character rule
    - it's mostly for readability
-


## JavaScript/ general programming

- [General best practices](https://github.com/airbnb/javascript)
  - also includes ESLint commands
- [Separation of Concerns](https://en.wikipedia.org/wiki/Separation_of_concerns)
- Guard clauses and putting conditionals that stop a function at the top
  - improves readability and logically makes more sense than sticking it at the bottom of a big `else if` chain

## Troubleshooting

- Check logs for error codes/ messages
  - npm has pretty good logging
- If its a package that's giving problems, check the Issues section of its repository
  - or try downgrading Node/ npm via nvm
- 
