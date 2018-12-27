# R in Linux Mint

Installing R and RStudio in Linux Mint is not really difficult, but there are certain requirements that must be installed from terminal if you want to have the latest version updated from CRAN repositories.

### Add R-base repository

```
sudo apt-get install gedit
sudo gedit /etc/apt/sources.list
```

### Add this line:

```    
deb [trusted=yes] https://cloud.r-project.org/bin/linux/ubuntu bionic-cran35/
```
### Update repositories and install r-base

```
sudo apt-get update
sudo apt-get install r-base
```

### Install requirements for tidyverse

```
sudo apt-get install libxml2-dev libcurl4-openssl-dev libssl-dev build-essential g++
```
