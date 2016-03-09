iped2-infrastructure
===

これはiPED2のインフラを構築するためのスクリプト群です。

## Description

iPED2には、開発環境と本番環境の二つのインフラがあります。
開発環境はVirtualBox上の仮想マシンを使って構築します。
本番環境はAmazon Web Service上に構築します。

## Requirement

* vagrant
* virtualbox
* aws cli

## Usage

```
$ vagrant box add bento/centos-6.7
```

## Install

```
$ git clone https://github.com/iped2/iped2-infrastructure.git
```

## Licence

[MIT](https://github.com/iped2/iped2-infrastructure/blob/master/LICENSE)

## Author

[中垣健志](nakaken0629@gmail.com)
