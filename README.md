# GhimireBuild
Yocto post build script based on python. 

It takes basic output of Yocto build and creates sd card, eMMC images and Software development kit 

In addition it also adds md5sum and sha256 checksum to secure the download 

## Requirements 


###python-pip
```
sudo apt-get install python-pip
```

### gitpython 

```
pip install gitpython
```