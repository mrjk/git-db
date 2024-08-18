# Git DB

A simple shell script to read and write ini file with git.

## 💻 Installation

The current latest version is: 0.0.4

### Dependencies

You need to have git installed.

### Install via ASDF or Mise

Can be installed by both `mise` or `asdf`:
```bash
mise plugin install git-db https://github.com/mrjk/asdf-git-db.git
mise use git-db

# With asdf
asdf plugin add git-db https://github.com/mrjk/asdf-git-db.git
asdf install git-db latest
asdf global git-db latest
```

### Install via Curl

Install it via curl:
```bash
curl -o git-db https://raw.githubusercontent.com/mrjk/git-db/main/git-db
chmod +x git-db
mv git-db /usr/local/bin/git-db
```

### Install from Source

Install via git:
```bash
git clone https://github.com/author/git-db.git
cd git-db
chmod +x git-db
ln -s git-db /usr/local/bin/git-db
```

### Verify installation

Should be able to get `git-db` version and help message:
```bash
git-db --version
git-db --help
```

## 🚀 Quickstart

### Basic Usage

TODO
