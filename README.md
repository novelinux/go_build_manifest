# Miot Open Platform Repo Manifest

## repo

```
$ mkdir ~/bin
$ vim ~/.bashrc

add PATH=~/bin:$PATH to the end of ~/.bashrc

$ curl http://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
```

## download sources

### openplatform-go-builder

```
$ repo init -u git@v9.git.n.xiaomi.com:liminghao/manifest.git -m openplatform-go-builder.xml
```