# hello-twelf
Examples from Chris Martens' course on [Logical Frameworks](https://chrisamaphone.github.io/lf-class/).

### Installation (Mac)

##### Required
```
git clone https://github.com/standardml/twelf && cd twelf
brew install smlnj
export PATH=/usr/local/smlnj/bin:"$PATH"
make smlnj
bin/twelf-server
(try loadFile <file>)
```

##### Recommended
```
brew install rlwrap
rlwrap bin/twelf-server
(try loadFile <file>)
```