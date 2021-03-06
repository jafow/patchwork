# Install

## One-click install, patchwork bundled with electron.

### For OSX

Download the latest .dmg file from [patchwork-electron/releases](https://github.com/ssbc/patchwork-electron/releases)

### For Ubuntu/debian

Download the latest .deb file from [patchwork-electron/releases](https://github.com/ssbc/patchwork-electron/releases)
and install with Ubuntu Software Center.

## From NPM

NPM hosts the stable release.
It will be the least likely to have bugs.

**Dependencies:**

 - node v5.3.x (you might like to use [nvm](https://github.com/creationix/nvm))
 - npm v3.5.x ([Instructions to update NPM when using NVM](#updating-npm))

**Install:**

``` bash
npm install ssb-patchwork -g
```

**Run:**

```bash
patchwork
```

Then open `localhost:7777`.


## From Git

GitHub hosts the development version.
It will contain updates not yet published on NPM.

**Dependencies:**

 - node v5.3.x (you might like to use [nvm](https://github.com/creationix/nvm))
 - npm v3.5.x ([Instructions to update NPM when using NVM](#updating-npm))

**Install:**

```bash
git clone https://github.com/ssbc/patchwork.git
cd patchwork
npm install
```

**Run:**

From directory you cloned patchwork to:

```bash
npm start
```

Then open `localhost:7777`.

**Update:**

From directory you cloned patchwork to:

```bash
git pull origin master
npm install
```


## Updating NPM

Some people experience installation issues when using the npm version packaged with node 5.3.0. We have found upgrading to npm 3.5.x solves these issues.

If you are using nvm, you can update npm with the following steps:

``` bash
cd ~/.nvm/versions/node/v5.3.0/lib
npm install npm
```
