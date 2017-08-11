## How to use this app for your own project

1. Clone the repo
2. `cd` into cloned repo and install stuff using:

```bash
$ yarn
$ sudo npm install -g ionic cordova
$ ionic start myTabs tabs
```

Then, to run it:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

For testing on chrome

```bash
$ ionic serve
```

Substitute ios for android if not on a Mac.
