Yocto for odroid

Clone repositories

```
$ repo init -u https://github.com/michal915/odroid-yocto
$ repo sync
```

Setup build-enviroment

```
source setup-env <build-directory>
```

Build image

[Supported boards](https://github.com/mecno/meta-odroid)

```
MACHINE=odroid-xu3 bitbake core-image-minimal
```
