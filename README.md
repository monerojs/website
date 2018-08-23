# monerojs website
[monerojs.org](https://monerojs.org) and [monerojs.com](https://monerojs.com)

```bash
npm install -g firebase-tools && firebase serve --only hosting
```

## Getting started

Install [firebase-tools](https://github.com/firebase/firebase-tools):

```bash
npm install -g firebase-tools
```

Test locally:

```bash
firebase serve --only hosting # emulates local hosting code
```

*(must use the `--only ...` flag to serve latest content)*

Login to Firebase prior to deployment:

```bash
firebase login
```

*(must have been added as a contributor to the Firebase project `monerojs/website`)*

## Firebase Hosting

### Usage

```bash
firebase serve --only hosting
```

Serves the webpage

### Deployment

```bash
firebase deploy --only hosting
```
