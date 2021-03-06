# Yarn-Selective-Upgrade
This allows selectively upgrading NPM packages filtered by upgrade type, package type, includes list, exclude list.

Installation
-----

The Yarn-Selective-Upgrade tool can be downloaded from github, made executable and added to your path with these commands:

#### ➤ Download the script and save it to /usr/local/bin
```bash
curl -o /usr/local/bin/yarn-selective-upgrade \
  https://raw.githubusercontent.com/sofyansitorus/Yarn-Selective-Upgrade/main/yarn-selective-upgrade
```

#### ➤ Make script executable
```bash
chmod +x /usr/local/bin/yarn-selective-upgrade
```

#### ➤ Check if it works
```bash
yarn-selective-upgrade --help
```

How to Use
-----
This command need to be run in your package.json directory.

#### ➤ Default mode
```bash
yarn-selective-upgrade
```

#### ➤ Wizard mode
```bash
yarn-selective-upgrade -w
```

# Credits

This project is made possible by the community surrounding it and especially the wonderful people and projects listed in this document.


## Libraries

### [The semver shell utility](https://github.com/fsaintjacques/semver-tool)

<details>
  <summary>Apache License 2.0</summary>

    https://github.com/fsaintjacques/semver-tool/blob/master/LICENSE

</details>
