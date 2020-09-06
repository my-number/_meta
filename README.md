# My-number metarepo for development

## How I made it

the repository name I want to name & the directory name I want to use in development is different.
So I made it for the mapping for them.

## How to start developing

```sh
git clone --recursive https://github.com/my-number/_meta myna
```

## Packages

- connect-lib
  - https://github.com/my-number/connect-lib
- lib
  - https://github.com/my-number/myna
- connect-popup
  - https://github.com/my-number/connect
- daemon
  - https://github.com/my-number/mynad
- streamsha
  - https://github.com/my-number/streamsha
- chain
  - https://github.com/my-number/mynachain
- appv1
  - https://github.com/my-number/mynachain-app
- firebase-auth
  - https://github.com/my-number/firebase-auth
## Branch

- master
  - my current environment
- stable
  - The state that has been confirmed to build up successfully

## Development

```sh
cd myna/<proj name>
emacs path/to/file
git add .
git commit
git push
```

I sync up submodule sometimes. If I forget to update, feel free to request me to update.
