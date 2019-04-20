# gituser
Simple CLI tool to check username availability on Github.

## Installation

To install gituser on a Debian/Ubuntu based system, paste and run this in your terminal :

```
wget -P ~/usr/local https://raw.githubusercontent.com/jsagot/gituser/master/gituser
chmod +x ~/usr/local/gituser
```

If ~/usr/local is not already in your path, add it with : 

```
echo "export PATH=\${PATH}:~/usr/local" >> .bashrc
. ~/.bashrc
```

## Usage

In a terminal run the following :

```
gituser <username>
```
