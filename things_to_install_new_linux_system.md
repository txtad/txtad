# Tad Marko

Mostly notes here for now.

# Things to Install on a New Linux Mint / Ubuntu System

## General

```
sudo apt install htop emacs vim byobu git smartmontools dc barrier \
docker.io gnupg geeqie oathtool keychain sshfs gvncviewer grc
```

[Google Chrome](https://www.google.com/chrome/)

[Atom text editor](https://flight-manual.atom.io/getting-started/sections/installing-atom/)

## Dropbox

This is specific for Linux Mint:
```
sudo apt install dropbox nemo-dropbox python3-gpg
```

## Java Development

```
sudo apt install openjdk-17-jdk openjdk-17-doc openjdk-17-jdk-headless openjdk-17-source maven
```

Be aware that maven that is available in many Linux repositories is often not a sufficiently recent version.
In that case, download it from the [Apache Maven Download Page](https://maven.apache.org/download.cgi).
It is still a good idea to install the distro version using apt to get the necessary dependencies, then put the downloaded version in a local bin directory.

[Eclipse](https://www.eclipse.org/downloads/)

## General Development

```
sudo apt install autoconf g++ jq make meld source-highlight tidy
```

## Entertainment

```
sudo apt install spotify-client
```

## Network Troubleshooting

```
sudo apt install mtr nmap tcpdump
```

## VM

### VirtualBox

```
sudo apt install virtualbox virtualbox-guest-additions-iso
```

## Kernel Compile

```
sudo apt-get install libssl-dev libelf-dev
```
