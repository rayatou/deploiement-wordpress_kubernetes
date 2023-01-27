To install jx 2.1.150 see the [install guide](https://jenkins-x.io/getting-started/install/)

### Linux

```shell
curl -L https://github.com/jenkins-x/jx/releases/download/v2.1.150/jx-linux-amd64.tar.gz | tar xzv 
sudo mv jx /usr/local/bin
```

### macOS

```shell
brew tap jenkins-x/jx
brew install jx
```
## Changes

### Bug Fixes

* split command creates a new repo as public (dror) [#7535](https://github.com/jenkins-x/jx/issues/7535) 

### Issues

* [#7535](https://github.com/jenkins-x/jx/issues/7535) split command creates a new repo as public ([drorventura](https://github.com/drorventura))
