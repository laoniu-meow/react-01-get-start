# Getting Started with React.js
React.js is an open-source JavaScript library designed for building modern, interactive user interfaces. It’s especially well-suited for single-page applications where content needs to update dynamically without reloading the entire page. Developed and maintained by Meta (formerly Facebook) together with a large developer community, React provides a component-based architecture that makes it easier to create reusable UI elements and manage application state efficiently

Before building applications with React.js, you’ll need to set up a proper development environment. This ensures you have the right tools to create, test, and run your projects smoothly

[x] [Getting Started with React.js](#setting-started-with-eact.js)

[x] [Install node & npm](#install-node.js-and-npm)

---

## Install Node.js and npm
React requires Node.js to run. Installing Node.js also gives you access to npm (Node Package Manager), which is used to manage project dependencies

### What is Node.js?
Node.js is an open-source, cross-platform runtime environment that allows you to run JavaScript code outside of a web browser
[... Read more about Node.js](https://nodejs.org/learn/getting-started/introduction-to-nodejs)

### What is npm?
It stands for Node Package Manager (npm), and it is the official package manager and code registry for Node.js.When you install Node.js, npm is automatically installed on your computer. It is the world's largest software registry, containing over two million free blocks of code that developers share with each other.
[... Read more about npm](https://docs.npmjs.com/about-npm)

> In a real working environment, most development teams do not use the latest version until it has been tested and approved for upgrade. Therefore, we must also know how to install a specific Node.js version to align with the team’s setup

Example: The teams required to use 24.16.0

```bash
# 1. Verify Node and Npm version
node -v             # Output: v24.15.0 - current installed version
npm -v              # Output: 11.12.1  - current installed version

# Your environment did not show the version, which means Node is not yet installed
# 2. Download and install NVM (Only for one-time)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash

# 3. Reload Your Shell
source ~/.bashrc

# 4. List version
nvm ls-remote       # You should be find v24.16.0

# 5. Install a Specific Node.js Version
nvm install 24.16.0

```

```
Output after execute the nvm install:
Downloading and installing node v24.16.0...
Downloading https://nodejs.org/dist/v24.16.0/node-v24.16.0-linux-x64.tar.xz...
######################################################################################################################################################## 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v24.16.0 (npm v11.13.0)
```

---







# 6. Use a Specific Node.js Version
nvm use 18

# 7. Verify the active version
node -v

# 8. Set a Specific Version as Default
nvm alias default 18